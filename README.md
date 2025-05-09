# Requirement Analysis in Software Development

## Introduction

This repository serves as a foundational guide to the process of **Requirement Analysis** in software development. Requirement analysis is a crucial phase of the Software Development Life Cycle (SDLC), where stakeholders define, gather, analyze, and document the functional and non-functional requirements of a system.

By providing clear and structured insights—including user stories, use cases, and acceptance criteria—this repository helps ensure that software projects are aligned with user expectations and business goals. It is especially relevant for projects such as the Lagos Intranet or booking systems, where thorough analysis is key to success.

Topics covered include:
- Requirement Gathering and Elicitation
- Documentation and Modeling
- Functional and Non-functional Requirements
- Use Case Diagrams
- Acceptance Criteria

---

## What is Requirement Analysis?

Requirement Analysis is a fundamental phase in the Software Development Life Cycle (SDLC) that involves identifying, documenting, and managing the needs and expectations of stakeholders for a software product. This process ensures that developers and clients share a clear understanding of what the software should do and how it should perform.

### Importance of Requirement Analysis:

- **Clarity and Understanding**: It helps eliminate ambiguity by defining detailed system functionalities and expectations, fostering better communication between stakeholders and developers.
- **Scope Definition**: Establishes the boundaries of the project, which helps prevent scope creep and uncontrolled changes during development.
- **Foundation for Design and Development**: Serves as the blueprint for system design, architecture, and implementation.
- **Accurate Cost and Time Estimates**: Enables realistic planning by providing clear requirements that influence budgeting and scheduling.
- **Improved Quality Assurance**: Aligns development efforts with user needs, resulting in a higher quality end product that satisfies stakeholder requirements.
- **Risk Reduction**: Identifies potential technical and business risks early in the project, allowing for mitigation strategies.

---

## Why is Requirement Analysis Important?

Requirement Analysis plays a pivotal role in the success of any software project. Without clearly defined and understood requirements, development teams risk building a system that does not meet the needs of its users or stakeholders. Here are three key reasons why Requirement Analysis is critical in the Software Development Life Cycle (SDLC):

### 1. **Clear Communication and Understanding**
Requirement analysis ensures that all stakeholders—developers, clients, users, and project managers—share a mutual understanding of the system's purpose and functionalities.

### 2. **Accurate Planning and Estimation**
Well-defined requirements provide a solid foundation for estimating the time, budget, and resources needed for a project.

### 3. **Improved Product Quality**
Capturing detailed user needs early helps ensure the final product aligns with stakeholder goals and performs as expected.

---

## Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that ensure all stakeholder needs are thoroughly understood, documented, and validated. The five key activities are:

- **Requirement Gathering**
  - Conduct interviews with stakeholders to understand their needs.
  - Distribute surveys and questionnaires for broader feedback.
  - Organize workshops to collaborate and discuss requirements.
  - Observe users in their working environment.
  - Review existing systems and documentation for insights.

- **Requirement Elicitation**
  - Use brainstorming sessions to generate requirement ideas.
  - Conduct focus groups for detailed stakeholder input.
  - Develop prototypes to visualize and refine potential solutions.

- **Requirement Documentation**
  - Create a comprehensive Requirement Specification Document.
  - Write user stories that describe features from the user's perspective.
  - Develop use case diagrams to map user interactions with the system.

- **Requirement Analysis and Modeling**
  - Prioritize requirements based on business value and feasibility.
  - Conduct feasibility studies considering technical, financial, and time constraints.
  - Build models such as data flow diagrams or entity-relationship diagrams to illustrate system behavior and structure.

- **Requirement Validation**
  - Review documented requirements with stakeholders for accuracy.
  - Define acceptance criteria for each requirement to ensure completeness.
  - Establish traceability to confirm all requirements are addressed during development and testing.

---

## Types of Requirements

In software development, requirements are broadly categorized into two types: **Functional Requirements** and **Non-functional Requirements**.

### Functional Requirements

Functional requirements define specific behaviors and features the system must support.

**Examples for a Hotel Booking Management System:**

- **User Registration and Authentication:** Users should be able to create an account and log in securely.
- **Search Functionality:** Users can search for hotels based on location, dates, and preferences.
- **Room Booking:** Users can select available rooms and make bookings.
- **Payment Processing:** The system should handle payments through various methods (e.g., credit card, PayPal).
- **Booking Management:** Users can view, modify, or cancel their bookings.
- **Review System:** Users can leave reviews and ratings for hotels they have stayed in.


### Non-functional Requirements

Non-functional requirements specify the criteria that judge the operation of a system, rather than specific behaviors. They define how the system performs a function.

**Examples for a Hotel Booking Management System:**

- **Performance:** The system should load search results within 2 seconds.
- **Scalability:** The application must support up to 10,000 concurrent users without performance degradation.
- **Security:** User data must be encrypted, and the system should comply with data protection regulations.
- **Availability:** The system should have an uptime of 99.9% to ensure constant availability.
- **Usability:** The user interface should be intuitive and accessible to users with varying levels of technical expertise.
- **Maintainability:** The system architecture should allow for easy updates and maintenance without significant downtime.

---

## Use Case Diagrams

Use Case Diagrams are visual representations of how users interact with a system. They help define system scope and improve stakeholder communication.

### Benefits of Use Case Diagrams:
- Clarify system scope and interactions
- Improve communication between stakeholders
- Provide a high-level overview of system functionality
- Serve as a foundation for creating test cases

### Hotel Booking System Use Case Diagram:

![Use Case Diagram for Hotel Booking System](alx-booking-uc.png)

**Actors**:
- Customer
- Admin
- Hotel Manager
- System User

**Use Cases**:
All Actors should be able to Login and Logout, Update Profile, and Manage Password.
- **Customer**: Register, Login, Search Hotel, Make Booking, Cancel Booking, Make Payment, Write Review
- **Admin**: Manage Users, Manage Hotel, Manage Rooms, Manage Services, Manage Payments, Generate Reports
- **Hotel Manager**: Manage Hotel Details, Confirm Booking, Allot Rooms, Collect Payments,  View Reviews
- **System User**: Manage Rooms, Manage Services, Manage Payments, 

---

## Acceptance Criteria

Acceptance Criteria are the conditions that a software product must satisfy to be accepted by a user, customer, or other stakeholders. They serve as a formal agreement on what a feature should do and provide a clear basis for functional testing.

### Importance of Acceptance Criteria:
- **Clarifies Expectations**: Ensures that both developers and stakeholders understand the scope and behavior of a feature.
- **Guides Development**: Helps developers stay aligned with functional requirements and business goals.
- **Enables Test Planning**: Serves as a reference for writing test cases and verifying functionality.
- **Supports Agile Processes**: Commonly used in Agile environments to define the "Definition of Done" for user stories.

### Example: Checkout Feature in a Booking Management System

**Feature**: Checkout

**Acceptance Criteria**:
1. Users must be able to review their booking summary before finalizing payment.
2. Users must be able to enter and validate their payment information (credit card, PayPal, etc.).
3. The system must display a confirmation message upon successful payment.
4. A booking confirmation email must be sent to the user's registered email address.
5. The system must store the booking information in the user's account history.
6. If payment fails, the system should notify the user with an appropriate error message and allow retry.


