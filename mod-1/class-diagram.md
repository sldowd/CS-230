# Module 1 UML Class Diagram

```mermaid
classDiagram
Vehicle <|-- TwoWheeled
TwoWheeled <|-- Bicycle
class Bicycle {
    -gears  int
    -cost  double
    -weight  double
    -color  String
    +Bicycle()
    +Bicycle(String)
    +Bicycle(int)
    +Bicycle(int, double, double, String)
    +outputData() void
    +outputData(String) Bicycle
    +getGears() int
    +getCost() double
    +getWeight() double
    +getColor() String
    +setGears(int) Bicycle
    +setCost(double) Bicycle
    +setWeight(double) Bicycle
    +setColor(String) Bicycle
}