# What Is In This Repository?
This repository is home to the Automation API specification for Open Innovation Labs Push Button Infrastructure. Originally, it started as the home of all our Swagger / OpenAPI Specifications, System Designs and Documentation, but over time this repository was re-purposed to only contain the Automation API Specifications. This was after deciding that we should have smaller, more discrete repos. This repository needs to be migrated to a new one to make the name more declarative.

# What is Push Button Infrastructure (PBI)?

Push Button Infrastructure is a capability developed in the Open Innovation Lab to enable our participant to focus on feature development on day 1, not the details of the platform they are running. To help understand PBI at a conceptual level, we'll explore it using [bounded contexts](http://martinfowler.com/bliki/BoundedContext.html), a key modelling concept introduced in [domain driven design](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215). In order to keep things conceptual, we're not going to introduce the tools or technologies we use for PBI implementation. There are 4 bounded contexts in the PBI conceptual architecture:

* **User Interfaces**
  * Graphical frontends to the assets in the PBI ecosystem, built using a [backend for frontend approach](https://www.thoughtworks.com/insights/blog/bff-soundcloud)
* **Automation API**
   * A declarative contract for modelling the desired state of Automation Targets
   * This repository is used for the Automation API
* **Automation Engines**
   * Tools used to consume the Automation API contract and produce the desired state in Automation Targets
* **Automation Targets**
  * The technologies that we ultimately want to create/configure/provision/etc. with PBI


Here's how those contexts look graphically:
![alt text](images/PBI_Conceptual.png "PBI Conceptual Architecture")

# To Learn More or Start Contributing
If you're interested in contributing or simply learning more about why we've made certain design decisions. See the [contributor's guide](CONTRIBUTING.md). 

# To View an Example from End User View Point
If you are interested in seeing an example use case. See the [Example Walkthrough] (example_walkthrough.md).