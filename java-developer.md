List of interview questions for Java Developer role
---------------------------------------------------

**Java language and JVM**
- Describe access modifiers (private, protected, public) and differences between them.
- What is inheritance?
- Describe difference between interface and abstract class.
- Is it possible that one class can be both abstract and final at the same time?
- Describe how does Garbage Collector works.
- What are types of Garbage Collector? When to use which?
- Describe structure of Java Heap.
- Describe structure of JVM.
- Tell something about `hashCode()` and `equals()` methods. What contract they need to satisfy?
- Can `hashCode()` return constant value? Explain your answer.
- Can two objects have the same hashCode?
- When `obj1.equals(obj2)` is true, then is it possible that `obj1` and `obj2` have different hashCodes?
- Describe `StringBuilder` and `StringBuffer` classes. What are differences between them?
- Do you know `java.util.concurrent` package? Tell something about its contents.
- Do you know any frameworks for concurrent programming?
- Describe `volatile` keyword.
- Describe overriding and overloading. What are differences between them?
- Describe keywords `final`, `finally` and `finalize()`.
- What is immutable object and how can you create it?
- Does all properties of immutable object need to be final?
- What is the difference between creating `String` with `new` operator and literal?
- Describe checked and unchecked exceptions. What are differences between them? When can we use specific type of exception and why?
- How does `substring()` works inside?
- Which method you need to implement to use object as key in a `HashMap`?
- Where do equals and hashcode come in the picture during `get(...)` operation?
- What's the difference between `Executor.submit()` and `Executor.execute()` method
- Can you write thread-safe Singleton?
- Write code iterating over `HashMap`
- Is it better to synchronize critical section of `getInstance()` or whole `getInstance()` method?
- What's wrong with using `HashMap` in multithreaded environment?
- How to create, start, destroy and block Threads in Java?
- Do you know any thread-safe collections?
- How would you prevent client from directly instantiation your concrete class?
- What's the difference between `HashMap` and `HashTable`?
- How does `HashMap` works?
- Describe shortcuts: JNI, JNDI, JAAS
- Describe differences between `Filter` and `Servlet`
- Does `LocalDateTime` have information about time zone? If not, then how to define time zone?

**Spring**
- What bean scopes do we have?
- What's default bean scope?
- How many instances bean has by default?
- How can we wire beans and components?
- How can we inject components?
- How Spring wires components and beans under the hood?
- What's new in Spring Boot when we compare it to Spring Core
- What `@SpringBoot` annotation has under the hood?
- When we explicitly call a method without any annotation, which calls internally a method with `@Transactional` annotation, then the whole operation will be transactional? Explain why?
- Why injecting components via constructor (with `@Autowired` annotation) is better than injecting them via annotations on class attributes?
- When should we use aspects?
- How to create aspect and what should it have?
- How to create async operations?
- How to schedule operations?

**Design Patterns**

- What design patterns do you know?
- Describe facade/adapter/builder/{any} pattern.
- What's the difference between factory and abstract factory pattern?
- What is Singleton?

**Good software development practices**

- What good practices of software development do you know?
- When you take a look at the code how do you recognize if it's clean and well written?
- How would you design method in the right way?
- What is loose coupling?

**Programming Paradigms**
- Describe structural programming paradigm
- Describe Object-Oriented Programming paradigm
- Describe functional programming paradigm
- Describe reactive programming paradigm

**Multi-threading & Concurrency**
- What problems can we solve with multi-threaded programs?
- What problems do we have during writing multi-threaded programs?
- How to deal with problems occurring in multi-threaded programs?
- What multi-threaded programming models do you know?
- How do you implement different multi-threaded programming models in Java?

**Version Control Systems**
- What kind of Version Control Systems do you know?
- Do you think Git is better than other systems? Why?
- Can you work offline with Git?
- Can you work offline with SVN?

**Continuous Integration**
- What types of Continous Integration Servers do you know? Have you used any?
- How did you used Jenkins or other CI Server in your work?

**Software development methodologies**
- In what methodologies did you work?
- Do you know scrum? Describe it.
- Can you describe kanban model?
- Can you describe waterfall model?

**Testing**
- What types of tests do you know?
- What is the difference between mock and stub?
- Do you know any libraries for mocking? Describe them.
- Do you know any libraries for testing? Describe them.
- What annotations of JUnit do you know and what is their purpose?
- How would you test method, which has to use implementation of method from another class, which is not ready yet?

**Web Services**
- Describe SOAP.
- Describe REST.
  - What request methods can you use for getting/inserting/updating/deleting data?
  - What is common protocol for REST
  - How good RESTful end-point should look like?
  - What are principles of designing good RESTful API?
  
**Others**
  - What operating system do you prefer and why?
  - What are news introduced in Java 8?
  - What are news introduced in Java 9?  
  - What technical book did you read recently?
  - What are your methods for learning new things?
  
