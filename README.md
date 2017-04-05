# jsr-330-cdi-guice-spring-dagger2
Sample JSR-330 project demonstrating how to run with CDI (Weld), Guice, Spring and Dagger2

JSR-330 is an API allowing the programmer to hint to the Dependency Injection engine how
dependencies should be injected.

This proof-of-concept project demonstrates how this can be used with real code.  Notably:

* Configuration parameters can be supplied at runtime.
* Each non-trivial dependency is resolved by the same code snippet for all engines.
* Actual DI-engine specific glue is kept separately for each engine.
* Standard Maven 3 build.
* Tested with IntelliJ 2017, Eclipse 4.6.2 and Netbeans 8.1

