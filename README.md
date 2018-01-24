# design_patterns-GoF
Indexes of GoF Design Patterns

** Cites from [dofactory](http://www.dofactory.com/net/design-patterns)

```
<b>Creational Patterns**</b>
```
Pattern | Short Description | Definition
--------|-------------------|-------------
Abstrct Factory | Creates an instance of several families of classes | Provide an interface for creating families of related or dependent objects without specifying their concrete classes
Builder | Separates object construction from its representation | Separate the construction of a complex object from its representation so that the same constrution process can create different representations
Factory Method | Creates an instance of several derived classes | Define an interface for creating an object, but let subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.
Prototype | A fully initialized instance to be copied or cloned | Specify the kind of objects to create using a prototypical instance, and create new objects by copying this prototype.
Singleton | A class of which only a single instance can exists | Ensure a class has only one instance and provide a global point of access to it.

```
Structural Patterns
```
Pattern | Short Description | Definition
--------|-------------------|-------------
Adapter | Match interfaces of different classes | Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn't otherwise because of incompatible interfaces.
Bridge | Separates an object's interface from its implementation | Decouple an abstraction from its implementation so that the two can very independently.
Composite | A tree structure of simple and composite objects |  Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly. 
Decorator | Add responsibilities to objects dynamically | Attach additional reponsibilities to an object dynamically. Decorators provide a flexible aternative to subclassing for extending functionality.
Facade | A single class that represents an entire subsystem | Provide a unified interface to a set of interfaces in a subsystem. Façade defines a higher-level interface that makes the subsystem easier to use.
Flyweight | A fine-grained instance used for efficient sharing | Use sharing to support large numbers of fine-grained objects efficiently.
Proxy | An object represnting another object | Provide a surrogate or placeholder for another object to control access to it.

```
Behaviroral Patterns
```

Pattern | Short Description | Definition
--------|-------------------|-------------
Chain of Resp. | a way of passing a request between a chain of objects | Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving obects and pass the request along the chain until an object handles it.
Command | Encapsulate a command request as an object | Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.
Interpreter | A way to include language elements in a program | Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language.
Iterator | Sequentially access the elements of a collection | Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.
Mediator | Defines simplified comunication between classes | Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it lets you vary their interaction independently.
Memento | Capture and restore an object's internal state | Without violating encapsulation, capture and externalize an object's internal state so that the object can be resotred to this state later.
Observer | A way of notifying change to a number of classes | Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
State | Alter an object's behavior when its state changes | Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.
Strategy | Encapsulates an algorithm inside a class | Define a family of algorithms, encapsulate each one, and make them interchaneable. Strategy lets the algorithm vary independently from clients that use it.
Template Method | Defer the exact steps of an algorithm to a subclass | Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.
Visitor | Defines a new operation to a class without change | Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.
