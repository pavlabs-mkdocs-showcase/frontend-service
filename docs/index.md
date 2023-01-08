# Frontend

This is the frontend service implemented in React and TypeScript that serves the UI of our application

```plantuml
@startuml
left to right direction
skinparam packageStyle rectangle
skinparam monochrome true
actor customer
rectangle frontend {
  customer .> (home page)
}
@enduml
```