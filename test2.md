# UML Diagram for UAT Space Program

without signature vs with sig

```mermaid
    classDiagram
    class Shape{
        -length
        +getLength()
        +setLength()
    }


    class ShapeWithSig{
        -length : int
        +getLength() : int
        +setLength(n : int) : void
    }

```

Attributes come before the attribute or method<br>
\+ public, \- private, \# protected<br>

```mermaid
    classDiagram
    class Superclass{
    }

    class Subclass1{
    }
    class Subclass2{
    }
    Superclass <|-- Subclass1 : Superclass Subclass relation
    Superclass <|-- Subclass2
```
cntl + shift + v to preview<br>
based on https://mermaid-js.github.io/mermaid/#/
