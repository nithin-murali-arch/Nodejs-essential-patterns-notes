# Nodejs-essential-patterns-notes


## Design patterns:

### Reactor pattern

The standard Reactor allows a lead application with simultaneous events, while maintaining the simplicity of single threading. 


### Callback/Observer pattern

The observer pattern (a subset of the asynchronous publish/subscribe pattern) is a software design pattern in which an object, called the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods. It is mainly used to implement distributed event handling systems.


### Producer consumer pattern
The Producer Consumer pattern is an ideal way of separating work that needs to be done from the execution of that work. As you might guess from its name the Producer Consumer pattern contains two major components, which are usually linked by a queue. This means that the separation of the work that needs doing from the execution of that work is achieved by the Producer placing items of work on the queue for later processing instead of dealing with them the moment they are identified. 

### Factory(Virtual Constructor)
Define an interface or abstract class for creating an object but let the subclasses decide which class to instantiate

Revealing Constructor
Proxy/Surrogate
Decorator
Adapter
Strategy
State
Template
Middleware
Command
Chain of Responsibility
Intercepting filter
Singleton
Interleaving
GoF


## To read

nodejs architecture
event demultiplexer
libuv libev libeio
CommonJS
dependency hell
Continuation passing style
circular dependencies
difference between exports and module.exports
duck typing
stamp specification
Function hooking(AOP)
Meta programming
operator overloading
object virtualization
CSRF
CORS
composable factory pattern
inversion of control
Asynchronous Module Definition
Universal module definition
Gulp, grunt, webpack
Caching mechanisms
sticky load balancing
upstart

## Reads
libuv resource - nikhilm.github.io/uvbook
Closures - developer.mozilla.org/en-US/docs/Web/Javascript/Guide/Closures
Unleashing Zalgo - blog.izs.me/post/5914272143/designing-apis-for-asynchrony
mrale.ph/blog/2012/09/23/grokking-v8-closures-for-fun.html
nodejs.org/docs/v0.10.0/api/http.html#http_agent_maxsockets
promiseaplus.com/
tc39.github.io/ecmascript-asyncawait
github.com/Izzimach/react-three
github.com/iamdustan/react-hardware


bluebird
promise.all
promise.race
map reduce
babel-cli for async await
Streams
.apply function
proxy

## Load Balancing
peer to peer load balancing

## Application Architecture
monolithic vs microkernel design
elastic microservice
Scale X,Y,Z
Reliability nodejs
Zero downtime restart
pm2


## Lambda Function providers
seneca
awslambda
apache mesos

## Messaging Architecture
api proxy
api orchestration
message broker

## Message Queues
QoS
MQTT
AMQP
STOMP
RabbitMQ(AMQP)
zeromq

## Wiring Modules
Hardcoded dependency
Dependency injection
Service locator
Dependency Injection containers


## NFRs

Reusability, maintenance, usability

## Key Phrases
Functions are first class objects
Callback last
Error param first
