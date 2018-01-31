
##  CSCI 5828:Foundations of Software Engineering Homework 1

#### Collaborators:
- Shemal Somil Lalaji
- Rakesh Shivanand Margoor

**Q.1) Define the term essential difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty. <br>
Ans:<br>**
    Brooks  mentioned that **there is no Silver Bullet in Software Engineering**. That means that there is no single development in software technology like in the field of Hardware, that by itself promises tenfold improvement within a decade.
     Brooks considered the difficulties that we encounter while developing a software product as being divided into two types of categories:<br>
 - Essential difficulties  <br>
 - Accidental difficulties <br>
  
 Essential difficulties as defined by Brooks are **the ones that are inherent in the nature of the software. This involves the data sets,algorithms,functions and relationship among the data entities. These may be the same in many different representations, but each of them is highly detailed and precise**. <br>
 
   Essential difficulties are caused by the problem defintion and if the client wants the software to do something, then the software has to accomplish the required task. For example, to represent the entire software in a single piece of paper with all its specifications,data flow,control flow and other entities which define the software . This represents one type of essential difficulty.<br>
   
   With a lot of debugging and code refactoring, we can reduce accidental difficulties(not entirely to zero) but the essential difficulties will always remain in the software. Due to this building a software is always going to be hard and hence comes the notion of No silver bullet being present in the field of software technology.<br>
<br>
**Q.2) Define the term accidental difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.<br>
Ans:<br>**
   As Brooks divided the difficulties into essential and accidental, let us consider the accidental difficulties:<br>  
   Accidental difficulties are the **ones which are related to the production of the software**. These are the ones which are created by the engineer who is building the software system and also corrected by the engineer. However while resolving these difficulties with the help of software tools, new ones may arise. So Brooks mentioned that we cannot **reduce accidental difficulties to absolute zero**.<br>
    
  Most of the tools in software engineering are **focussed on resolving these accidental difficulties**. According  to Brooks,**one technology that had reduced accidental difficulties was the invention of high-level programming languages, such as FortRan**.Brooks  also mentiones that **reducing the accidental difficulties would not give the same order of improvement as compared to reducing the essential difficulties and thereby the concept of no silver bullet arises as some order of essential difficulties will always sort of persist in the system.**<br>
  
  An example of accidental difficulty is: Say we build a mobile application and while using the mobile application the host mobile loses a lot of battery power. This can be fixed by an update or iteration in the software. This is an example of accidental difficulty.<br>
  <br> 
  **Q.3) List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.<br>
  Ans:<br>**
        The four essential difficulties of developing software systems that Brooks identifies are:
  - complexity  
  - conformity 
  - changeability  
  - invisibility<br>
  Let us discuss all of these in detail:<br>
     - **Complexity**
         While constructing a software , one has to develop a large number of different software entities or subparts of a large software program.If one was developing the same thing then we can reuse it by building a function or method according to object oriented or functional programming. So as the scope of the software increases,the number of different entities also increases and thereby also increases interactions between the different software entities. This increases work in the software especially in the case of when a bug arrives when different components of the software have to be integrated.For example, if different people wrote different functions of a large code and an error is visible when an entire system is integrated, every developer has to read the function code of the other developers. This increases the complexity of the project and pushes the project scope into jeopardy. So this is a type of essential difficulty.<br>
      - **Conformity**
         Conformity relates to the essence in which the software is build.Lets say we started building a software application using Python 2.7. However after a certain while, the policies of the company changes and the new policies supported building software using Python 3.5. So the entire code that has been developed in Python 2.7 has to be changed to Python 3.5. So the software has to conform to the new requirements. This is a form of essential difficulty which affects the timeline of the software significantly and may change the scope of the project under consideration.
       - **Changeability**
         Software is always destined to change. At any moment of time, software can be improved or be asked to change based on the functions it executes. Change in the software can lead to generation of bugs as the components of the software tend to interact with each other. So errors cause due to changes can propogate through the entire software project.Change in software requirements can also be disastrous in the middle of software development.So this is an essential difficulty. One can avoid this by adopting either an agile framework which supports changes in general or iterative development which changes the software in its next iteration after completing one full iteration of a particular software product.<br>
        - **Invisibility:**
         The internal structure of a software is very complicated and not visible to the human eye. When we execute a software, what we tend to see is the working of the components of the software. However the components itself cannot be seen,feel or heard. The internal nature of the software is therefore said to be hidden to the end user. We can use to represent the software using UML(Unified Modeling Language),Class diagrams or Data flow diagram(DFD). However all of these give information about the flow of information inside the system. The flow of other things such as memory,current is invisble to the user. Thus the software is hidden to the user and we cannot eliminate that as it constituents the fundamental structure of the software. Hence this is a form of essential difficulty.
         
        
**Q.4) Define what Brooks means by a silver bullet and reconstruct his argument as to why he believes there is no silver bullet for software engineering.<br>
  Ans:<br>**
  According to Brooks , **there are no silver bullets in software engineering**. He explained silver bullet as i**nventions that will do tenfold improvement in software productivity, reliability, and simplicity like electronics, transistors, and large-scale integration did for computer hardware**. He further states that **one cannot expect ever to see twofold gains every two years as happens in hardware according to Moore's law**.
<br>
  This means that there is no out of the world cure for improving the software gain by one order of magnitude or 10x improvement.This 
 is due to the two types of difficulties:essential and accidental.According to Moore, **the hard part of building software is the specification, design, and testing of this conceptual construct, not the labor of representing it and testing the fidelity of the representatio**n. Because of this, software building is always very hard.<br>
    Most tools in software engineering tend to solve the accidental difficulties and try to reduce it to as small as possible. However essential difficulties still remain and they cannot be avoided as it will destroy the essence of software.So considering these two difficulties will always be present **one magical cure cannot improve the performance tenfold**.<br>
    According to Brooks, **the very nature of software and the complecity imbibed within it makes it difficult to have tenfold improvement**. Brooks argument makes sense as if there was any silver bullet , the improvement in software engineering would have been very rapid. Instead, we all tend to design tools to fix bugs or errors present in the system. The requirements of the software tend to be complicated and no tool can help to reduce this complexity as well as eradicating these requirements will destroy the purpose of the software. So unless one can develop a magical tool that can not only eradicate each and every bug and decrease the complexity of the requirements, one has to use a combination of tools and software engineering techniques to combat the software problem.  
  
  **Q.5) In lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.<br>
  Ans: <br>**
  Let us first describe the relationship between a chemist (chemistry) and a chemical engineer (chemical engineering):<br>
  A chemist or field of chemistry gives us the exciting formulas and derivations developed throughout the years. A chemical engineer makes use of these methods in his own personal project in a manner that respects the project requirements. Some of these derivations have to be either combined to form a new derivation or even constrained a bit to achieve the result. For example, limiting the pH level of a substance requires combination of the acid and base in some proportions modeled relative to the outside world pH level.<br>
  Now, software engineering and its relationship to computer science can be defined using the same analogy:<br>
  Computer science is the combination of several concepts such as Operating Systems,Algorithms,Networking,Databases and many more. Each of these facets give fancy stuff that can be used. However in the real world the problem often requires a combination of these concepts and there are some external constraints such as cost which forces us to modify the fancy stuff to suit our goal. Software Engineering is the field which incorporates the requirements or constraints and considering the goal makes use of the fancy stuff in an ideal way.For example: we want to transfer content from one computer to another. This makes use of networking to send the packets via routers. Along with these we may need to incorporate some sort of security mechanism to make sure the packet is received by the intended recipient. We may also need some type of scheduling algorithm at the receiver side. So all these processed together constitute a software and defines the process of software engineering.
   
  **Q.6) In lecture, we discussed the importance of the following concepts to software engineers: abstractions, conversations, specification, translation, and iteration. Define each of these concepts as they are related to software engineering and discuss their importance.**
   **Ans: <br>**
- **Abstractions:**
Abstraction in software engineering is creating a simple higher level interface to a combination of complex sub-systems. 
Abstraction reduces the additional effort that has to be put in understanding the complexities of the multiple lower level systems and also avoids any duplication of a program or software. 
It can also be used to break the problem into several understandable modular problems. Abstraction is a very important concept in Software Engineering as it helps in parallelizing, sharing, and reusing of the already built software. 
Another advantage of using abstraction can be security. 
Abstraction can be used to hide internal implementation of libraries or packages and yet make them available for others to use. 
An interesting example of how abstraction simplifies the software engineering process can be depicted by considering the use of storing a file into a database. In order to store a file into a database, a file system is required. Now, while implementing file storage in DB, worrying about how to create a file system is a very low level problem and spending time on it makes the task more complicated. Instead, if we already have an abstraction of the file system, the same abstraction/API can be used by multiple developers to implement the required file storage feature in a DB.

- **Conversations:**
Conversation is one of the key characteristic in software engineering which involves discussion among the customers, clients, developers and many others who are associated in the development of a given product. The conversation of the development team with the client ensures the specification is up to date. The conversation among the development team is also important as there are various instances where each other’s work is interdependent. To make sure the work done by one is used smoothly by the other, a detailed conversation either through face to face, or through documentation on tools like rally, Jira or pivotal has to be performed.

- **Specifications:**
Specification is one of the core principles of software engineering which drives the implementation of a software. 
Specification is required at all levels of software Engineering which includes requirements, code, design, test plans, development life cycles.
Requirements generally can be in the form of business proposals, product description and various other specifics regarding the corresponding software.
With no requirements, the project does not exist, as there are no set of goals that have to be achieved. 
A good specification avoids changeability problem, brings transparency between the client and the developers, reduces redundant work and importantly helps to plan, schedule and achieve the required software.
Specifications at code level are also a critical factor, as it determines the use of abstraction and allows parallel development.
Since a project is developed in modules by several developers sitting at different places; programming languages, their versions, the hardware and the developer environment has to be specified before it's implementation else
a considerable amount of work has to be spent to integrate each other's work and would make the entire process complex, unstable and time consuming.
In order to verify whether the built software has met all requirements, there has to be specification on how the tests are performed which should cover all scenarios of how the software can break. 
A detailed specification on test-plans ensures no faulty software released into production.
Hence, specification is a key role in the evolution of a software and appears at all stages of software engineering. 

- **Translation:**
Unlike hardware, software goes through a lot of changes during its course of time. The changes might be due to changes in the requirements, design, project structure etc. In order to accommodate these changes, the project goes into translation very often. Software cannot have a fixed blueprint throughout its implementation. Due to the continuous change in technologies, demand, Manpower and various other factors, translation is one of the important principles that a software has to adopt in order to be robust and flexible at all stages.

- **Iteration:**
Every big project is implemented by dividing the project into subprojects with goals that can be achieved through a single step from a small unit of the development team. 
Iteration is thus breaking down the software development into smaller chunks and repeating the cycles regularly. The main advantage of the iteration is to allow more flexibility for changes.
With iteration, the project goes through a cycle where a detailed evaluation is performed to determine if any changes have to be considered to produce a satisfactory product at the end.
Thus, the analysis on each iteration ensures that the project is leading in the right direction, and if not, an immediate and early stage of rectification is ensured. This avoids a late turning back when a considerable amount of work is performed and the product has to go through a revision.
Iterative development is a key practice in the agile development methodology and it has been adopted in corporate development and has successfully resulted in a better software development cycle.

 #### REFERENCES:
- http://sebokwiki.org/wiki/The_Nature_of_Software
- https://en.wikipedia.org/wiki/No_Silver_Bullet
- http://worrydream.com/refs/Brooks-NoSilverBullet.pdf
- http://wiki.c2.com/?NoSilverBullet
- https://blog.acolyer.org/2016/09/06/no-silver-bullet-essence-and-accident-in-software-engineering/
 
