# PatternAcademia
Interactive App for learning OOP and Design Patterns

1. Project description
PatternAcademia is an interactive educational platform designed to help students understand Object-Oriented Programming (OOP) principles and Software Design Patterns.
The application will provide structured lessons, practical Java code examples, UML class diagrams, interactive simulations, and exercises to evaluate students' knowledge.
Additionally, the platform will integrate an AI-powered chatbot that allows students to obtain assistance with understanding programming concepts and design patterns.

2. Project objectives
The main objectives of PatternAcademia are:
- Provide educational materials covering OOP and Software Design Patterns.
- Explain programming concepts through theoretical lessons and practical Java examples.
- Illustrate software structures using UML diagrams.
- Provide interactive simulations to demonstrate object interactions.
- Evaluate students' knowledge through quizzes and exercises.
- Integrate an AI chatbot that provides explanations and answers questions related to the educational content.
- Demonstrate the practical application of object-oriented principles and design patterns in software development.
- 
3. Target users
The application will support two types of users:
- Student: Can access lessons, explore code examples and UML diagrams, interact with simulations, complete exercises, and use the AI chatbot.
- Administrator: Can manage educational content, including lessons, code examples, diagrams, and exercises.

4. Functional requirements
The system shall provide the following functionalities:
-	User management: Allow users to register, log in, and manage their accounts.
-	Educational content: Provide lessons covering OOP and Design Patterns.
-	Code examples: Display Java implementations with explanations.
-	UML diagrams: Display diagrams illustrating the structure and relationships of software components.
-	Interactive simulations: Allow students to visualize object interactions step by step.
-	Exercises and quizzes: Provide interactive questions to evaluate students' understanding.
-	Answer evaluation: Evaluate submitted answers and provide feedback.
-	AI chatbot: Allow students to ask questions and receive AI-generated explanations.
-	Learning progress: Track completed lessons and quiz results.
-	Content management: Allow administrators to create, update, and delete educational materials.

5. Educational content
Object-Oriented Programming
- Encapsulation
- Inheritance
- Abstraction
- Polymorphism
Software Design Patterns
- Creational: Singleton, Factory Method, Abstract Factory, Builder, Prototype
- Structural: Adapter, Decorator, Facade, Composite, Proxy
- Behavioral: Strategy, Observer, Command, State, Iterator

6. Non-functional requirements
The application shall satisfy the following requirements:
- Usability: Provide an intuitive and easy-to-navigate interface.
- Performance: Respond efficiently to user interactions and database operations.
- Security: Protect user accounts and restrict administrative functionality to authorized users.
- Reliability: Handle errors without interrupting the application's operation.
- Maintainability: Follow a modular architecture with clearly separated responsibilities.
- Extensibility: Allow new lessons, examples, exercises, and design patterns to be added easily.
- Compatibility: Support commonly used web browsers, if implemented as a web application.

7. Technical specifications
The application will be implemented using Java and object-oriented programming principles.
Proposed technologies:
Programming language - Java
Backend framework - Spring Boot
Frontend - Thymeleaf, HTML, CSS, JavaScript
Database - PostgreSQL
Database access	- Spring Data JPA / Hibernate
Authentication - Spring Security
AI integration - External AI API
Build management - Maven
Testing	- JUnit and Mockito
UML diagrams - PlantUML

The application will follow a layered architecture consisting of:
- Presentation layer: Handles the user interface and user interactions.
- Service layer: Implements the application's business logic.
- Data access layer: Handles database operations.
- Database: Stores users, educational content, exercises, and learning progress.
- AI integration component: Handles communication with the external AI service.

8. Expected results
The final result will be a functional educational platform that enables students to study OOP principles and software design patterns through theoretical materials, Java examples, UML diagrams, interactive simulations, and exercises.
The integrated AI chatbot will provide additional learning support by answering questions and explaining programming concepts.

The project will also demonstrate how object-oriented programming principles and design patterns can be applied to develop modular, extensible, and maintainable software.
