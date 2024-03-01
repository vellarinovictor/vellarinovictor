# Portfolio  
## En este portfolio ire incluyendo todas las herramientas y conocimientos clave que vaya adquiriendo.  

  En materia de Entonos de desarrollo, puedo realizar diagramas de comportamiento, y también puedo trabajar bajo una metodología Kanban o Scrum. Me desenvuelvo bien en Git.  
  También estoy en proceso de aprender Java. Ahora mismo controlo las bases: tipos de datos, estructuras de selección y de control. Ahora mismo estoy trabajando con clases y objetos.  
  Para páginas webs estoy aprendiendo HTML5, pero no tengo ninguna página subida a la red todavía.  
  Fuera del curso estoy aprendiendo herramientas No-Code, ahora mismo estoy con Webflow, para crear páginas webs de forma visual e intuitiva, veo mucho potencial en estas herramientas.  
  Puedo usar y configurar bases de datos en Microsoft Access, así como diseñar bases de datos y normalizarlas.  
  En [PROGRAMACIÓN](https://github.com/vellarinovictor/PROGRAMACION) se encuentran todos mis proyectos actualmente en Java.

classDiagram
  class ElectricEquipment {
    + name: String
    + performOperation(): void
    + showGeneralInformation(): void
    + toString(): String
  }

  class PowerGenerator {
    + capacity: int
    + performOperation(): void
    + toString(): String
  }

  class TransmissionLine {
    + length: int
    + performOperation(): void
    + toString(): String
  }

  class ElectricSupplyProgram {
    + main(args: String[]): void
  }

  ElectricEquipment <|-- PowerGenerator
  ElectricEquipment <|-- TransmissionLine
  ElectricSupplyProgram --> ElectricEquipment

  style ElectricEquipment fill:#77DD77
  style PowerGenerator fill:#66B2FF
  style TransmissionLine fill:#66B2FF
  style ElectricSupplyProgram fill:#FFD700
