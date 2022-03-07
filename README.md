# SOA

It stands for **service-oriented architecture**.

## What it is ?

- One thing we need to know is that SOA is not a technology. It is **_architecture_**.
- I can say methodology to building systems.
Which most IT giants use to handle their enterprise more effectively and in a more agile way.
- SOA is a **middleware solution**. Middleware solution means **which makes two or more systems or applications to talk to each other**.

## How it works ?

- When we say SOA, we can think soa in two-way services plus messages.

### Let us understand with one example,

- **Suppose one _Japanese_ boy wants to talk with a _Chinese_ girl. But they don't know each other's language. So how do they communicate with each other?**

  - _So There will be one mechanism or some translator which will translate the Japanese language to the Chinese language or vice versa. In this way, they will communicate with each other._
  - _So, the same thing will happen in our integration like there will be two or more systems and if they want to talk with each other. We will have an SOA between them._

## Advantages

- SOA is a **loosely coupled architecture**.

  - This means when systems talks with each other the dependency required to talk is **minimal**.

  - Failure of one system does not impact another system._

## Mechanism before and after SOA

### Let us understand with one example

_Before SOA was invented also we were talking to each other right that is not the case like earlier when SOA was not invented we were not talking to each other we were waiting for SOA when SOA will come we will integrate our system that is not the case._

 So, Earlier there were several technologies one of the things which were or which is **P2P (Point To Point)** integration.

### **What is the point-to-point integration do?**

- Suppose, **system1** which is developed in **java** and **system2** developed in **python** and they want to talk with each other so in point-to-point integration, system1 directly connects with system2 and they will talk with each other. this is the scenario and point-to-point integration.

- Suppose this connection breaks then the whole failure occurs in the system or suppose we want to add one new system **system3** which is developed in **.Net.** then, what will be the scenario we need to connect the **system3** with **system1** and also with **system2** so, the system3 needs to establish the connection between **three to one** and **three to two**. so, **this is also a time-consuming thing** right so that was the scenario.

- If we keep on increasing the system then connection needs to establish and connection will grow exponentially. so, it looks good when the number of systems to integrate is less.

- So, **when we have less system then that is fine in point-to-point integration**. but suppose we will have many systems to integrate there will be a problem.

### Advantage of SOA Integration

- **System1 does not need to know System2**. so, that is the **advantage** of using **SOA**.

- So, If **system1** just need to pass our message to SOA layer which we want to pass **system2**. then SOA will do all the transformation needed thing or message passing related things to **system2**. That's the advantage of using **SOA**.

- One main advantage is when we pass our message to **SOA** and suppose **one system failure or system connection failure occurs**. What SOA does is, **SOA is smart enough to send this message when system2 is available**. _SOA will retry the message passing to the system when it is available_.

## Key points about SOA

- **system1** is required to integrate with **system2**. This **systems does not need to know each other**.

- **System1** needs to transfer data to SOA somehow, then SOA is capable to transform the data provided by **system1** to the **_understandable format_** of **system2**.

- **If a new system comes then it only needs to plugin with the SOA layer**. suppose one new system system3 comes. What we need to do is **we don't need to connect system1 and system2**. we just need to plugin that **system3** to SOA layer. **then all connectivity will occur in this whole system**.

- When some **System fails then SOA can store and retry those requests to the target system when it is available.**


## Resource & Reference

- [Oracle](https://www.oracle.com/technical-resources/articles/javase/soa.html)
- [IBM](https://www.ibm.com/in-en/cloud/learn/soa)
- [Youtube](https://youtu.be/ypiJXjqPea8)
- [Youtube](https://youtu.be/tooRfyCHOT0)