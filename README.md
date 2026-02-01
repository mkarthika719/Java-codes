Java OOP Concepts Explanation
1. Encapsulation
Encapsulation is the concept of hiding internal details of an object and providing controlled access to its data. In your project, the Car class demonstrates encapsulation. The car’s fuel level and engine status are private, meaning they cannot be changed directly from outside the class. Methods like startEngine, drive, refuel, and stopEngine provide controlled access and ensure the car behaves correctly.
 For example, the engine only starts if there is fuel, and driving reduces fuel safely. This protects the car’s internal state from invalid operations.

3. Inheritance
Inheritance allows a class to reuse properties and methods from another class. In the project, Vehicle is the parent class with general vehicle properties and actions. Sedan and Truck are child classes that inherit these properties and methods but also add their own unique features. Sedan adds the number of doors and the ability to open the trunk, while Truck adds cargo capacity and four-wheel drive. Both subclasses also override the honk method to customize behavior. This demonstrates how inheritance promotes code reuse and hierarchy.

3. Polymorphism
Polymorphism allows objects of different types to be treated uniformly, while still behaving according to their specific type. In the project, Vehicle is the base class, and SportsCar and PickupTruck are subclasses that override methods like starting the engine and driving. The TestDriver class can test drive any vehicle type without knowing its exact class. When a sports car or pickup truck is passed, it executes the overridden methods automatically, showing dynamic behavior at runtime.

4. Abstraction
Abstraction focuses on what an object can do rather than how it does it. In the project, the Drivable interface defines the actions of any drivable vehicle, such as starting, steering, accelerating, braking, and turning off. ManualCar implements these actions for a human-driven car, while AutonomousCar implements them for a self-driving car. Despite different implementations, both cars follow the same interface. This demonstrates how abstraction hides complex details while providing a uniform way to interact with objects.

