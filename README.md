# helpnotes

1. How to structure DDD go app?

Domain: This is where the domain and business logic of the application is defined.
Infrastructure: This layer consists of everything that exists independently of our application: external libraries, database engines, and so on.
Application: This layer serves as a passage between the domain and the interface layer. The sends the requests from the interface layer to the domain layer, which processes it and returns a response.
Interface: This layer holds everything that interacts with other systems, such as web services, RMI interfaces or web applications, and batch processing frontends.

3. What's the best framework for go app? 
