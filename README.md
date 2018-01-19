![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/webmvclogo.png)
# webmvcframework - PHP WEB MVC Framework
The package webmvcframework, with the acronym of **WebMVC**, is an **object oriented** PHP framework that uses**MVC architectural design pattern** for building web applications with MySQL database and HTML.

It offers to developers a complete set of functionalities for rapid development of data intensive web applications. Generally, it provides services for system decomposition that developers can do at different levels when they coding a complex web application. Firstly it entire implements services for realizing the MVC design pattern decomposition between PHP code and the HTML code of the GUI. However, this is not the only feature provided by the Framework for acting on the application's decomposition.

The **Component Based Development**, used for building many Framework’s features, permits to developers another more level of applications decomposition and software reuse. Framework’s components, in fact, realize common **Aspects** that can occurs, in a similar way, into different web applications. Many of these aspects are regarding database, for example: data listing, data listing and sorting, data listing and filtering, data listing and pagination, record management and common table’s operations for select, insert, delete and update records. Framework offers a set of pre-built components for implementing the necessary server logic for these common database management aspects.These components are itself MVC objects with a Controller, are easy to use and developers can aggregate them into a root controller by using a composite criteria for building complex application pages. A component GUI can also easily adapted or replaced to reflect the application’s experience simply by modifying or replacing its HTML template with a custom one. Component’s server logic will remain fully reusable without the need of any source code modifications.

## How to install
To install download and copy it into an Apache web folder. Then go to the config directory and modify application.config.php according to your MySQL server configuration and Apache web folder you used to deploy your application.
By default framework provides some examples.
I will provide you more examples of all functionalities, in a future time.

## How to autogenerate PHP Model classes from your MySQL database
The util directory contains a file named **app_create_beans.php**.
Run it from your browser or from command line for executing ORM classes code auto generation regarding tables of a given MySQL database.

Warning !
Before running it you must configure MySQL access parameters by modifying **util\mysqlreflection\mysqlreflection.config.php** according to your MySQL configuration.
After running the utility you can find the autogenerated PHP classes into the **models\beans directory**.

### Documentation

####  WebMVC official wiki
Tou can start to read the wiki form [here](https://github.com/rcarvello/webmvcframework/wiki)

#### Other information
You can dowload some PDFs, PPTs, and diagrams from [here](https://github.com/rcarvello/webmvcframework/tree/master/docs)

#### Video Tutorial
An introduction to PHP WebMVC Framework   

[![IMAGE Video Tutorial](https://i.ytimg.com/vi/7zJFXLd4rk8/hqdefault.jpg?custom=true&w=196&h=220&stc=true&jpg444=true&jpgq=90&sp=67&sigh=5Dym90YTR05kyX82Kg8gW9VseUk)](https://www.youtube.com/watch?v=7zJFXLd4rk8&t=37s)

### Diagrams

#### Main classes
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/framework.png)

#### Handling HTTP requests - Loading and dispatching controllers
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/Dispatch%20and%20Create%20MVC%20Instance.png)


