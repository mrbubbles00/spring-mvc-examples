Spring-MVC Examples
===================

Simple examples demonstrating the basic features of Spring-MVC using both pre-2.0 XML based configuration style
and the latest Spring 3.x annotation-driven style.

Also demonstrates basic JSON enabled web services using both a pre-RESTful query-parameter based style with Spring 1.2.x 
and a RESTful web services style with Spring 3.x.

### Examples

* [hello-spring-mvc](hello-spring-mvc) - Bare minimum Spring MVC application using a JSP view with JSTL support.
* [multi-action-controller-example](multi-action-controller-example) - Simple web application using MultiActonController.
* [json-view-example](json-view-example) - Render JSON responses using a Jackson-based JSON marshalling view.
* [json-binding-example](json-binding-example) - Bind HTTP POST data to model objects using a JSON HTTP request reader.
* [spring3-example](spring3-example) - A modern Spring-MVC application using autowiring and MVC annotations (@Controller, @RequestMapping, etc.)
* [spring3-json-example](spring3-json-example) - Example RESTful JSON web service using the built-in Jackson object mapping support in Spring 3.

### The Example Application

The examples are based on a simple library application that can add then edit a single book.

![Library State Diagram](https://github.com/jfarr/spring-mvc-examples/raw/master/src/site/library_state_diagram.png)

**Library Application State Diagram**

### Testing the JSON Examples

The JSON examples include sample [RESTClient](http://code.google.com/p/rest-client/) requests in the src/test/resources 
folder that can be used to test sending JSON data to and retrieving data from the JSON web service. The sample requests
assume that the application server is running on port 8080, so may need to be modified for your development environment.
