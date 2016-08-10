# arduino-helpers
A set of Arduino libraries for easily components handling

## Purpose
The idea of this project is to centralize several submodules I am working with, that lets any developer to deal with some
electronic components (Arduino compatible) in a higher level manner. So, for example, instead of being thinking of "sending a HIGH to a digital output",
a developer should think of:

1. Create an instance of a particular component `LED led = LED(ledPin);`
2. Lights on: `led.on();`

By thinking the components helpers as *instanceable* classes, then the components are variables that can be passed as parameters in methods, allowing the developers to write smart code for building their projects.

Take a look at each submodule documentation for a quick start.

## Spirit

By creating an Open Source project, and putting some basic examples, I'm intending to get other helpers by contributors and put these all together within this project.