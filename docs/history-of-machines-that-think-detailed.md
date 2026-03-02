# **From Calculation to Computation: A History of the Machines That Think**

Co-Authored by Alireza Goudarzi and Gemini Pro 2.5 | Edited by Alireza Goudarzi

## **Prelude**

While diverse backgrounds enrich group thinking and problem-solving, a lack of shared terminology, concepts, and mental models can impede effective communication and lead to misunderstanding.

At **Shingane**, we operate at the intersection of software, hardware, artificial intelligence, and its foundations in machine learning. Although professionals from software and hardware engineering often have some familiarity with the early development of modern computers—and with the theoretical groundwork laid by Alan Turing—many may not realize that the very concept of artificial intelligence is deeply intertwined with the history of computing. In fact, the modern framework for computation emerged from a thought experiment exploring the nature of thought itself, first introduced in the seminal paper *"Can Machines Think?"*

This piece aims to provide a brief history of computing and its key milestones—from early calculation to modern computation. Our goal is to build a shared mental model for how we understand computing, trace its evolution, envision its future, and recognize how we at Shingane are contributing to that journey.

## **Introduction**

The history of computing is a narrative of profound intellectual evolution, a dynamic interplay between two fundamental human drives: the practical necessity to solve tangible problems and the abstract, philosophical quest to understand the very nature of logic, proof, and thought. It is a story that stretches from the dusty counting boards of ancient Sumeria to the silicon heart of the modern digital age. This journey is a complex tapestry woven from threads of engineering ingenuity, mathematical genius, and philosophical crisis. The computer, as we know it today, is not merely a machine that performs arithmetic at superhuman speed; it is a universal machine capable of manipulating symbols according to a set of rules. The articulation of this concept—the separation of the ***process*** from the ***processor***, of ***software*** from ***hardware***—required millennia of development in both the physical and metaphysical realms. 

## **Origins of Computation – From Pebbles to the Heavens**

The history of computing begins long before electricity, in humanity’s effort to manage numbers and predict the world. From the beginning, two distinct paths emerged. One dealt with the *discrete and countable*—separate units that could be tallied, traded, and stored. The other dealt with the *continuous and uncountable*—the flowing cycles of time, motion, and the heavens. These parallel traditions gave rise to the first true computational devices.

The abacus, first seen in Sumer around 2700 BCE, turned arithmetic into a physical process. Pebbles placed in columns represented units, tens, and higher values, allowing quick addition, subtraction, multiplication, and division. It worked with the discrete: clear, separate quantities that could be counted and arranged. Over centuries, the design spread and improved—from Greek counting boards to the Chinese suan-pan and Japanese soroban. For thousands of years, it was the world’s main digital calculator, answering the question: *“How many?”*

The Antikythera Mechanism, discovered in a Greek shipwreck and dated to the 2nd century BCE, represents the other path. With more than 30 bronze gears, it modeled the movements of the Sun, Moon, planets, and eclipses. By turning a hand-crank, the operator could predict celestial events and track long cycles of time. Unlike the abacus, it worked with the continuous: smooth, ongoing changes that could not be broken into simple counts. It was the earliest known analog computer, answering the question: *“Where will it be?”*

These two devices mark the first milestones in computing. The abacus shows the digital tradition of discrete steps, while the Antikythera Mechanism shows the analog tradition of continuous modeling. Together, they reveal how the two great streams of thought—counting and predicting, digital and analog—developed side by side, eventually converging in the modern computer.

## **The Mechanical Age – Automating Arithmetic and Logic**

For centuries after the Antikythera Mechanism, mechanical ingenuity found expression in clocks, orreries, and special-purpose devices. But by the 19th century, the demands of industry, science, and global trade created a new problem: the need for vast, accurate mathematical tables. Producing these by hand was slow and error-prone. The challenge was no longer just calculation, but the automation of reasoning itself.

Charles Babbage was the first to face this challenge head-on. In the 1820s, he designed the **Difference Engine**, a massive calculator intended to produce tables automatically and error-free. Using the method of finite differences, it could evaluate polynomials by repeated addition, eliminating the need for human computers. Though never completed in his lifetime, later reconstructions proved its design was sound.

Yet while working on this machine, Babbage conceived something far more ambitious: the **Analytical Engine**. Described in 1837, it was not just another calculator but the first design for a **general-purpose programmable computer**. Its architecture foreshadowed the modern computer:

* a **Store** (memory),

* a **Mill** (processor),

* an **input system** using punched cards,

* and a **printer** for automated output.

What made it revolutionary was **programmability**. Borrowing the punched-card concept from the Jacquard loom, Babbage separated the machine’s hardware from the instructions it followed. With operation cards, the same machine could be reconfigured to solve entirely different problems. It even supported branching and loops—the essential features of modern programming.

Ada Lovelace, translating and annotating Babbage’s work, recognized its true significance. In her 1843 notes, she described an algorithm for calculating Bernoulli numbers, now regarded as the first computer program. She saw that the machine could manipulate not just numbers, but any symbols—laying the foundation for the idea of a universal computer.

The leap from the Difference Engine to the Analytical Engine marks the turning point from **special-purpose calculators** to the **concept of a programmable machine**. Though never built in his time, Babbage’s vision contained the DNA of modern computing: the separation of hardware and software, and the idea of a universal engine limited only by the programs it could run.

## **The Theoretical Crucible: Defining the Limits of Computation**

The 19th-century vision of a mechanical computer, though complete in Babbage’s designs, never materialized. Progress toward modern computing did not come from engineering advances alone but from abstract work in mathematical logic and philosophy. To build a computer in principle, one first had to define precisely what “computation” and “proof” mean. This definition emerged from a foundational crisis in mathematics that overturned the dream of absolute certainty and exposed the limits of mechanical reasoning.

### **The Search for Foundational Certainty**

At the start of the 20th century, David Hilbert launched a program to place all of mathematics on a rigorous axiomatic basis. His goals were:

* **Consistency** – no contradictions within the system.

* **Completeness** – every true statement provable within the system.

* **Decidability** – a “definite method” (algorithm) to determine truth or falsity.

This last aim was formalized as the **Entscheidungsproblem** (“decision problem”). Hilbert’s vision was, in effect, a universal machine for mathematical proof. His program paralleled the logical positivism of the Vienna Circle, both movements driven by faith in logic as the secure foundation of knowledge.

### **Gödel’s Incompleteness: The Limits of Logic**

Hilbert’s dream collapsed in 1931 when Kurt Gödel published his **First Incompleteness Theorem**, showing that any consistent system capable of basic arithmetic contains true statements that cannot be proven within it. His **Second Incompleteness Theorem** went further: such a system cannot prove its own consistency. Together, these results revealed that the goals of completeness and provable consistency were impossible.

### **The Decision Problem and the Turing Machine**

Only decidability remained. To address the **Entscheidungsproblem**, Alan Turing in 1936 defined a formal model of computation: the **Turing machine**. It consists of an infinite tape, a read/write head, and a finite control unit governed by rules. Despite its simplicity, Turing argued that it captured all effective procedures[^1],[^2]. This became the **Church–Turing thesis**: if a problem could be solved by a human following a finite set of clear, precise steps, then a Turing machine could also solve it.

Turing proved that the **halting problem**—determining whether a given machine halts or runs forever—is undecidable. Since solving the Entscheidungsproblem would solve the halting problem, the Entscheidungsproblem itself is undecidable.

The pivotal concept in Turing’s work was the **Universal Turing Machine**, a device able to simulate any other Turing machine by treating program descriptions as data. Conceived for a logical proof, it became the abstract model of the general-purpose, stored-program computer. Ironically, the failure of Hilbert’s program gave rise to the very idea of universality that underlies all modern computation.

## **The First Generation: From Theory to Electromechanical Reality**

The theoretical breakthroughs of the 1930s—Gödel’s incompleteness theorems and Turing’s model of the Universal Machine—defined the logical limits and possibilities of computation. The Second World War provided the urgency and resources to turn these ideas into physical machines. The 1940s marked the birth of large-scale, automatic digital computers: first electromechanical, then fully electronic. Central to this transition was the architectural leap from machines with external programs to the revolutionary stored-program computer.

### **Babbage’s Dream in Electromechanical Form: The Harvard Mark I**

The IBM Automatic Sequence Controlled Calculator (ASCC), or Harvard Mark I, became operational in 1944 at Harvard University under Howard Aiken. Built with IBM, it was a 51-foot-long electromechanical giant with 750,000 components and 500 miles of wiring, powered by a single 5-horsepower motor. Operators nicknamed it “Bessie” for the constant clicking of its relays.

Architecturally, the Mark I echoed Babbage’s Analytical Engine: separate storage counters for numbers, a dedicated arithmetic unit, and instructions stored externally. Its programs were read from punched paper tape—a defining feature later termed the **Harvard architecture**, where data and instructions remain physically separate.

The Mark I ran continuously for the U.S. Navy, calculating ballistics tables, torpedo designs, and even contributing to the Manhattan Project. It also trained pioneers such as Grace Hopper, who introduced concepts like loops by literally gluing paper tape into continuous cycles.

### **The Stored-Program Revolution: The Von Neumann Architecture**

While the Mark I represented the peak of electromechanical design, a new idea was emerging that would reshape all future computers. In 1945, John von Neumann’s *First Draft of a Report on the EDVAC* articulated the stored-program concept: instructions should reside in the same memory as the data they manipulate. This design—developed with J. Presper Eckert and John Mauchly at the University of Pennsylvania—became the foundation of the **Von Neumann architecture**, still used today.

The architecture consists of:

* A Central Processing Unit (CPU) with an Arithmetic Logic Unit (ALU) and Control Unit (CU).

* A single Memory Unit for both instructions and data.

* Input/Output mechanisms.

* Buses to move information between components.

Its defining feature is the **unified memory**: instructions and data stored together. This eliminated the slow, inflexible punched tapes of Harvard-style machines. Programs could be loaded, modified, or replaced in seconds. It also enabled self-modifying code and paved the way for compilers, debuggers, and operating systems. The downside was the “Von Neumann bottleneck”: instructions and data share the same bus, limiting throughput.

This unification of program and data was more than an engineering trick—it embodied the earlier theoretical insights. Gödel had shown with Gödel numbering that statements of logic could be encoded as numbers. Turing’s Universal Machine read the description of another machine—its program—from its tape. The Von Neumann architecture translated these insights into hardware: instructions became just another kind of data.

From that point forward, computers became universal. A new function no longer required rewiring a machine; it only required loading a new program. This stored-program principle—simple yet profound—is the reason one physical computer can serve as a calculator, word processor, database, or game console. It is the engineering realization of the Universal Turing Machine.

### **Microprocessors and Personal Computers: The shift from Hardware to Software and The Birth of Computer Science**

The invention of the stored-program computer marked a profound shift in computation. Early machines, from the Harvard Mark I to ENIAC, had realized Babbage’s dream: performing calculations automatically. But programs were often external, manually encoded, and tightly bound to the hardware. The development of transistors and microprocessors in the 1970s miniaturized this power, turning room-sized machines into chips small enough for personal computers. Intel’s 8086/8088 processors, combined with IBM’s decision to use them in the IBM PC, brought general-purpose stored-program computing to desktops worldwide. For the first time, universal computers were accessible, affordable, and capable of running a wide variety of software, establishing a platform where programs, rather than machines, drove innovation.

This shift gave birth to software as a discipline and, with it, computer science. Programmers were no longer constrained to solving one specific problem at a fixed size—they could now devise algorithms: abstract, step-by-step procedures capable of handling infinitely many instances. Sorting a list of arbitrary length, searching networks of any size, or computing primes for any range became problems that could be solved with a general algorithm, independent of a particular machine or dataset. The development of data structures—ways to efficiently organize and manage information—followed naturally, enabling programs to tackle increasingly complex, variable, and large-scale problems.

In essence, the standardization of stored-program architecture shifted the center of gravity in computing from hardware to ideas. The machine provided a canvas; the algorithm, data structure, and program became the medium. Stored-program computers didn’t just automate arithmetic—they made the program itself the object of study, igniting the rise of software engineering, algorithm design, and the formal science of computer science.

---

## **Conclusion**

The journey from the abacus to the x86 microprocessor is a testament to the intricate and often unpredictable evolution of human thought and technology. It is a history that defies a simple chronological account of inventions, revealing instead a rich intellectual narrative driven by the persistent interplay of practical necessity and abstract inquiry. The story of computing is the story of humanity's centuries-long quest to mechanize reason itself—a quest that began with the simple act of counting pebbles, was given a soul by the visionary imagination of Charles Babbage, and found its universal form in the theoretical crucible of 20th-century mathematical logic.

The ancient world established the two great, parallel traditions of computation: the digital, embodied by the abacus for discrete arithmetic, and the analog, exemplified by the Antikythera Mechanism for modeling continuous cycles. For nearly two millennia, these streams ran largely separate courses. The Industrial Revolution, with its demand for error-free calculation, spurred Babbage to bridge this gap, conceiving first a masterwork of special-purpose mechanical calculation, the Difference Engine, and then the revolutionary, general-purpose Analytical Engine. His critical insight—the separation of the process (software) from the machine (hardware)—was the conceptual birth of the universal computer, though it remained a dream unrealized in his time.

The path to realizing that dream led not through the workshop, but through the lecture hall and the philosopher's study. The crisis in the foundations of mathematics, brought on by the ambition of Hilbert's program and the shattering revelations of Gödel's incompleteness theorems, forced a rigorous definition of computation. In solving a problem of pure logic, the *Entscheidungsproblem*, Alan Turing created the abstract model of the Universal Turing Machine. This theoretical construct, born from the failure to achieve perfect mathematical certainty, paradoxically provided the complete logical blueprint for a universal computing device.

The pressures of the Second World War finally translated this theory into practice. The Harvard Mark I realized Babbage's vision in electromechanical form, while the Von Neumann architecture provided the crucial engineering insight to embody Turing's universal machine in hardware by unifying program and data in a single memory. This principle, the treatment of instructions as data, is the foundation of all modern software. Finally, the miniaturization enabled by the silicon transistor culminated in the microprocessor. The rise of the Intel 8086 and its x86 architecture was not a foregone conclusion of technical superiority, but a contingent outcome of business pragmatism and the powerful network effects of the IBM PC ecosystem. It demonstrated that in the real world, standards are forged as much by the marketplace as by the laboratory.

Today, as we stand in an age increasingly defined by artificial intelligence and machine learning, this history is more relevant than ever. The fundamental questions about the nature and limits of computation, first posed with formal rigor by Gödel and Turing, are no longer abstract concerns of logicians. They are at the heart of our efforts to create machines that learn, reason, and perhaps one day, understand. The long journey from calculation to computation continues, and its next chapters are still being written.

#### **Works cited**

1. The Abacus and the Numeral Frame | National Museum of American History, accessed September 2, 2025, [https://americanhistory.si.edu/collections/object-groups/the-abacus-the-numeral-frame-and-counters](https://americanhistory.si.edu/collections/object-groups/the-abacus-the-numeral-frame-and-counters)  
2. History of Abacus \- AbacusMaster, accessed September 2, 2025, [https://abacusmaster.com/HistoryOfAbacus.aspx](https://abacusmaster.com/HistoryOfAbacus.aspx)  
3. Abacus \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Abacus](https://en.wikipedia.org/wiki/Abacus)  
4. Abacus-World's first calculator | History of Computers \- Cuemath, accessed September 2, 2025, [https://www.cuemath.com/learn/abacus-history/](https://www.cuemath.com/learn/abacus-history/)  
5. Antikythera mechanism \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Antikythera\_mechanism](https://en.wikipedia.org/wiki/Antikythera_mechanism)  
6. How the Secrets of an Ancient Greek 'Computer' Were Revealed, accessed September 2, 2025, [https://www.history.com/articles/antikythera-mechanism-ancient-computer-secrets](https://www.history.com/articles/antikythera-mechanism-ancient-computer-secrets)  
7. Antikythera mechanism | EBSCO Research Starters, accessed September 2, 2025, [https://www.ebsco.com/research-starters/physics/antikythera-mechanism](https://www.ebsco.com/research-starters/physics/antikythera-mechanism)  
8. Antikythera mechanism | Description, Purpose, & Facts \- Britannica, accessed September 2, 2025, [https://www.britannica.com/topic/Antikythera-mechanism](https://www.britannica.com/topic/Antikythera-mechanism)  
9. Planimeter \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Planimeter](https://en.wikipedia.org/wiki/Planimeter)  
10. Planimeter | Surveying, Measurement, Calculation \- Britannica, accessed September 2, 2025, [https://www.britannica.com/science/planimeter](https://www.britannica.com/science/planimeter)  
11. Pre-Amsler planimeters, accessed September 2, 2025, [http://persweb.wabash.edu/facstaff/footer/planimeter/PreAmsler.htm](http://persweb.wabash.edu/facstaff/footer/planimeter/PreAmsler.htm)  
12. Linear | National Museum of American History, accessed September 2, 2025, [https://americanhistory.si.edu/collections/object-groups/planimeters/linear](https://americanhistory.si.edu/collections/object-groups/planimeters/linear)  
13. Difference Engine Versus Analytical Engine // Unstop, accessed September 2, 2025, [https://unstop.com/blog/difference-engine-versus-analytical-engine](https://unstop.com/blog/difference-engine-versus-analytical-engine)  
14. Imagining AI \- Babbage & Lovelace | History of Science Museum, accessed September 2, 2025, [https://www.hsm.ox.ac.uk/imagining-ai](https://www.hsm.ox.ac.uk/imagining-ai)  
15. Analytical Engine | Description & Facts | Britannica, accessed September 2, 2025, [https://www.britannica.com/technology/Analytical-Engine](https://www.britannica.com/technology/Analytical-Engine)  
16. Analytical engine \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Analytical\_engine](https://en.wikipedia.org/wiki/Analytical_engine)  
17. Mathematical Problems of David Hilbert \- Clark University, accessed September 2, 2025, [http://aleph0.clarku.edu/\~djoyce/hilbert/](http://aleph0.clarku.edu/~djoyce/hilbert/)  
18. Entscheidungsproblem \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Entscheidungsproblem](https://en.wikipedia.org/wiki/Entscheidungsproblem)  
19. Hilbert's Problems: 23 and Math \- Simons Foundation, accessed September 2, 2025, [https://www.simonsfoundation.org/2020/05/06/hilberts-problems-23-and-math/](https://www.simonsfoundation.org/2020/05/06/hilberts-problems-23-and-math/)  
20. Gödel's Incompleteness Theorems (Stanford Encyclopedia of ..., accessed September 2, 2025, [https://plato.stanford.edu/entries/goedel-incompleteness/](https://plato.stanford.edu/entries/goedel-incompleteness/)  
21. Gödel's incompleteness theorems \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/G%C3%B6del%27s\_incompleteness\_theorems](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems)  
22. Vienna Circle | Logical positivism, Empiricism, Rationalism | Britannica, accessed September 2, 2025, [https://www.britannica.com/topic/Vienna-Circle](https://www.britannica.com/topic/Vienna-Circle)  
23. Vienna Circle \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Vienna\_Circle](https://en.wikipedia.org/wiki/Vienna_Circle)  
24. First Meeting of the Vienna Circle | EBSCO Research Starters, accessed September 2, 2025, [https://www.ebsco.com/research-starters/history/first-meeting-vienna-circle](https://www.ebsco.com/research-starters/history/first-meeting-vienna-circle)  
25. Logical positivism \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Logical\_positivism](https://en.wikipedia.org/wiki/Logical_positivism)  
26. Phil-of-Math-Logical-positivism-Vienna-Circle.pdf \- Jamie York, accessed September 2, 2025, [https://jamieyorkacademy.com/wp-content/uploads/bsk-pdf-manager/2023/05/Phil-of-Math-Logical-positivism-Vienna-Circle.pdf](https://jamieyorkacademy.com/wp-content/uploads/bsk-pdf-manager/2023/05/Phil-of-Math-Logical-positivism-Vienna-Circle.pdf)  
27. Can you solve it? Gödel's incompleteness theorem | Mathematics \- The Guardian, accessed September 2, 2025, [https://www.theguardian.com/science/2022/jan/10/can-you-solve-it-godels-incompleteness-theorem](https://www.theguardian.com/science/2022/jan/10/can-you-solve-it-godels-incompleteness-theorem)  
28. Turing Machines (Stanford Encyclopedia of Philosophy), accessed September 2, 2025, [https://plato.stanford.edu/entries/turing-machine/](https://plato.stanford.edu/entries/turing-machine/)  
29. Turing machine | Definition & Facts | Britannica, accessed September 2, 2025, [https://www.britannica.com/technology/Turing-machine](https://www.britannica.com/technology/Turing-machine)  
30. Turing machine \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Turing\_machine](https://en.wikipedia.org/wiki/Turing_machine)  
31. Raspberry Pi: Introduction: What is a Turing machine?, accessed September 2, 2025, [https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/turing-machine/one.html](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/turing-machine/one.html)  
32. Mark 1, rebooted \- Harvard SEAS, accessed September 2, 2025, [https://seas.harvard.edu/news/2021/07/mark-1-rebooted](https://seas.harvard.edu/news/2021/07/mark-1-rebooted)  
33. en.wikipedia.org, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Harvard\_Mark\_I](https://en.wikipedia.org/wiki/Harvard_Mark_I)  
34. Harvard IBM Mark I \- Function | Collection of Historical Scientific ..., accessed September 2, 2025, [https://chsi.harvard.edu/harvard-ibm-mark-1-function](https://chsi.harvard.edu/harvard-ibm-mark-1-function)  
35. Von Neumann architecture \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Von\_Neumann\_architecture](https://en.wikipedia.org/wiki/Von_Neumann_architecture)  
36. Von-Neumann Architecture \- DigiKey, accessed September 2, 2025, [https://www.digikey.com/en/maker/blogs/2024/von-neumann-architecture](https://www.digikey.com/en/maker/blogs/2024/von-neumann-architecture)  
37. Von Neumann Architecture \- Computer Science GCSE GURU, accessed September 2, 2025, [https://www.computerscience.gcse.guru/theory/von-neumann-architecture](https://www.computerscience.gcse.guru/theory/von-neumann-architecture)  
38. Intel 8086 \- Wikipedia, accessed September 2, 2025, [https://en.wikipedia.org/wiki/Intel\_8086](https://en.wikipedia.org/wiki/Intel_8086)  
39. Birth of a standard: The Intel 8086 Microprocessor \- PC World \- SteveMorse.org, accessed September 2, 2025, [https://stevemorse.org/pcw2b.html](https://stevemorse.org/pcw2b.html)  
40. The Intel 8086 is 45 years old, but was only meant as a stopgap \- Custom PC, accessed September 2, 2025, [https://www.custompc.com/intel-8086](https://www.custompc.com/intel-8086)  
41. Evolution of Microprocessor 8086? \- NITS GLOBAL, accessed September 2, 2025, [https://www.nitsglobal.com/blog/preview.php?pid=96\&p=](https://www.nitsglobal.com/blog/preview.php?pid=96&p)  
42. Unveiling the Past: Exploring the 8086 Microprocessor | by Ghulam Mustafa | Medium, accessed September 2, 2025, [https://medium.com/@gm-writes/unveiling-the-past-exploring-the-8086-microprocessor-b33b865a0499](https://medium.com/@gm-writes/unveiling-the-past-exploring-the-8086-microprocessor-b33b865a0499)  
43. The Intel ® 8086 and the IBM PC, accessed September 2, 2025, [https://www.intel.com/content/www/us/en/history/virtual-vault/articles/the-8086-and-the-ibm-pc.html](https://www.intel.com/content/www/us/en/history/virtual-vault/articles/the-8086-and-the-ibm-pc.html)

[^1]:  Effective procedure is any set of instructions that can be carried out mechanically and unambiguously, leading to a definite outcome.

[^2]:  A problem that could be solved with an effective procedure (by a Turing machine) is called Turing computable.