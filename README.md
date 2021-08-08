###<div style="text-align:center">Messaging Queue</div>
###Introduction
A queue is the line of things, and processing a task by sequential order. A message queue is the line of messages generate by user for other application. It process tasks in a sequential order i.e. first in first out(FIFO). It include the sequence of messages waiting in a queue. This enables messages to wait in a queue safely until the receiver is ready. So in between there is no problem if the receivers internet connection is not working, the messages are in messaging queue will not be lost. This model, referred to as asynchronous messaging, prevents data loss and enables systems to still function if processes or connections fail. This allows developers to stay processes and applications separate, keeping their communications self-contained and event-driven to form the architecture more reliable.
The basic architecture of a message queue is, client will generate the messages and deliver them to the message queue. Another Client, connects to the message queue and get this messages for processing. Messages placed on to the queue are stored until the consumer retrieves them.
<hr />
###Applications
1. Today’s enterprise computing environments are complex and highly decentralized. Messaging makes it easier to integrate applications and services on diverse platforms by providing a single, robust, and secure shared messaging backbone. This protects against data loss and ensures systems will continue to function even with unstable connectivity.
2. Message queues are suited for integrating backend systems with cloud services. In cloud architectures, applications are often broken down into small, independent components. This makes it easier to design and code them, and also easier to manage their performance. Message queues enable these decoupled cloud-based applications to communicate with each other or with on-premises systems.
3. Message queues work across disparate applications such as mobile, IoT, and traditional transaction system records.
<hr />
###Popular Tools
- MuleSoft Anypoint Platform.
- IBM MQ
- Azure Scheduler
- Apache Kafka
- TIBCO Rendezvous
- Google Cloud Pub/Sub
<hr />
###Enterprise Message Bus
An enterprise service bus (ESB) is a middleware tool used to distribute work to the all connected devices of an application. ESBs are designed to provide a uniform means of moving work, offering applications the ability to connect to the bus and subscribe to messages based on simple structural and business policy rules. As such, it's a tool that has use in both distributed computing and component integration. The best way to think of this tool is to visualize it as a set of switches that can direct a message along a specific route between application components based on message contents and implementation or business policies.




