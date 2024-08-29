# WACOMM - Whatsapp Communication System


> [!NOTE]
> The GitHub repository for this project cannot be shared publicly as it is part of a company project that I worked on.


## Overview


<b>WACOMM</b> is a SaaS product designed to serve as an endpoint for organizations to send WhatsApp messages to their customers through the WhatsApp Meta API. This application enables a single organization with multiple customer support members, using a single business account number, to manage and send various types of messages, including:
  * Individual messages
  * Bulk messages
  * Template messages
  * Photos
  * Videos
  * Webflows
  * Documents
Additionally, the system allows for the sending of both individual and bulk messages, including regular text messages, templates, and webflows.


## Features

* `Multi-User Support`: Multiple customer support representatives within an organization can utilize the system simultaneously under a single business account.
* `Versatile Messaging`: The system supports various types of media, including text, images, videos, and documents.
* `Role-Based Communication`: Users within the organization can communicate with customers, monitor these interactions, raise support tickets, and access detailed interaction data.
* `Automation Support`: The system supports the sending of automated messages via WA chatbot, templates, and webflows.
* `Raising Ticket`: Users can create a ticket for a customer's query and escalate it to higher authorities or the appropriate personnel when necessary.


## Tech Stack


The WACOMM system is built using the following technologies:

<b>Backend:</b>

* `FAST API`: For creating RESTful APIs.
* `Uvicorn`: An ASGI server for running the FastAPI application.
* `Pydantic`: For data validation and settings management.
* `SQLAlchemy`: For interacting with the PostgreSQL database using an ORM.
* `PostgreSQL`: The relational database used to store persistent data.
* `AWS SQS`: Used for message queuing to manage communication workflows.
* `SES Client`: AWS SES Client is used for sending transactional emails.
* `META WA API`: Integration with the WhatsApp Meta API for message sending.

<b>Frontend:</b>

* `React JS`: The JavaScript library used for building user interfaces.
* `ShadCN`: For UI component styling.


## Usage


<b>Sending Messages</b>

WACOMM allows users to send various types of messages:

* Single Individual Message: Send a direct message to a single customer.
* Bulk Messages: Send the same message to multiple customers simultaneously.
* Template Messages: Utilize pre-defined templates for consistent communication.
* Media Messages: Send images, videos, and documents as part of your communication.
* Webflows: Deploy web-based workflows to guide customer interactions.


<b>Role-Based Communication</b>

Users within the organization can have specific roles that allow them to:

* Communicate directly with customers.
* Monitor and log all interactions.
* Raise support tickets as necessary.
* Access detailed reports and logs for further analysis.


## Conclusion


WACOMM is a robust communication tool that streamlines customer interactions via WhatsApp, enabling organizations to manage their communication channels efficiently. With support for a wide range of message types and robust backend technologies, it is an essential tool for any organization looking to enhance its customer support capabilities.


### Thankyou
