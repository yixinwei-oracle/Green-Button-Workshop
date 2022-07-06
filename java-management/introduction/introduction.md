# Introduction

## About Java Management Service

Java Management Service (JMS) is a reporting and management infrastructure integrated with Oracle Cloud Infrastructure Platform services to observe and manage your use of Java SE (on-premises or in the Cloud). Lifecycle Management (LCM) is a part of JMS's reporting and management infrastructure. JMS enables users to observe and manage the lifecycles of their Java SE runtimes (on-premises or in the Cloud) by performing LCM operations such as Removing Java Runtimes.

Watch the video below for an introduction to Java Management Service and a brief demo.

[video of introduction to Java Management Service](youtube:YCgJxqvglCI)



As a customer, you can:

* Use insights from JMS to optimize your workloads across your enterprise (desktop, server, cloud); and
* Protect your Java SE investments by identifying outdated Java installations and unauthorized applications.
* View and identify the Java Runtimes.
* Install and remove Java Runtimes.
* View and understand various status and logs related to LCM work requests.

JMS helps systems administrators to answer questions such as:

* What are all the versions of Java I have running in development and production?
* Which vendors are providing the Java installations in my environment?
* Are my applications using their intended Java installations?
* Are unauthorized applications running?
* How many outdated Java installations do I have?

As the stewards of Java, Oracle can provide answers to these questions. Oracle uniquely leverages its expertise to gain critical insights into Java application behavior, compliance, and performance.

## About this Workshop

 This workshop will walk you through the process of setting up and using Java Management Service (JMS) on Oracle Cloud Infrastructure (OCI). It will first walk you through the process of creating a fleet, which is the primary collection with which you interact when using JMS and contains Managed Instances that share a common management approach. It will then get guide you through the process of setting up the Management Agent on a host machine to monitor Java applications and view them inside a fleet in JMS. Next, you will learn how to install and remove a Java Runtime using OCI console and cancel or view a work request. You will also get to view status and logs related to delete work requests. Finally, the workshop will show you how to view and monitor Lifecycle Management requests.

*Estimated Time:* 60 minutes

### Objectives

* Creating a Fleet
* Installing Management Agent on OCI computes using Oracle Cloud Agent (OCA)
* Understanding and performing LCM operations with JMS

### Prerequisites

* This workshop requires an Oracle Cloud account. You may use your existing account or create one in the following lab.

## Extension Workshops

If you would like to learn more about using JMS together with other OCI services, you may explore [Integrate OCI Services with Java Management Service](https://apexapps.oracle.com/pls/apex/dbpm/r/livelabs/view-workshop?wid=3203).


## Learn More

* [Getting Started with Java Management Service](https://docs.oracle.com/en-us/iaas/jms/doc/getting-started-java-management-service.html)
* [Java Runtime Lifecycle Management](https://docs.oracle.com/en-us/iaas/jms/doc/java-runtime-lifecycle-management.html)
* [Announcing Java Management Service](https://blogs.oracle.com/java/post/announcing-java-management-service)


## Acknowledgements

* **Author** - Alvin Lam, Java Management Service
* **Last Updated By/Date** - Yixin Wei, July 2022
