<h3 align="center">System Design Basics</h3>

<div align="center">

</div>

---

## 📝 Step Guide for System Design

- Requirement Analysis - Functional requirements (what this system should do). Non-functional requirements (how the system should behave).
- API design - Here we define the interfaces we expose to the outside world using which the communication happens. Here we have to define the name of the apis, the parameters it takes and the return values.
- Define data model – It is a representation of object data, its association between different objects and the rules it should follow.
- High level design – This depicts the required component blocks with arrows showing the data flow. The components can be load balancers, web servers, application servers, databases, caches or custom components performing some action like filtering, reading, processing , etc. The high level design shows how the data flows from an entry point to a database and vice versa.
- Scale the design – This is necessary because today’s systems are generally large scale distributed systems. To process large data we need to add multiple machines since it is difficult or rather impossible for one single machine to do everything. You need to find all the bottlenecks and fix them.

## ✍️ Credits <a name = "credits"></a>

- [The Complete Design Interview Course](https://completedesigninterviewcourse.com/system-design-interview/)