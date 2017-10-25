# Java---Project-Jigsaw
My first Java 9 module


mkdir src\edu.greetings\edu\chinna\kadira

javac -d mods\edu.greetings src\edu.greetings\module-info.java src\edu.greetings\edu\chinna\kadira\Greetings.java

java --module-path mods -m edu.greetings/edu.chinna.kadira.Greetings

