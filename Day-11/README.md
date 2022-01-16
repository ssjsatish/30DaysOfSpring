# Aspect Oriented Programming in Spring (AOP)
Aspects are a way the framework intercepts method calls and possibly alters the execution of methods. You can affect the execution of specific method calls you select. This technique helps you extract part of the logic belonging to the executing method.

<br/>

## Working of aspects
An aspect is simply a piece of logic the framework executes when you call specific methods of your choice. When designing an aspect, you define the following:

1. What code you want Spring to execute when you call specific methods. This is named an ***aspect***.

2. When the app should execute this logic of the aspect (e.g., before or after the method call, instead of the method call). This is named the ***advice***.

3. Which methods the framework needs to intercept and execute the aspect for them. This is named a ***pointcut***.