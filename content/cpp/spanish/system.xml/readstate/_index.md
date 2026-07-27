---
title: ReadState
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica el estado del lector.
type: docs
weight: 703
url: /es/system.xml/readstate/
---
## Enumeración ReadState


Especifica el estado del lector.

```cpp
enum class ReadState
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Initial | 0 | El método [XmlReader::Read](../xmlreader/read/) no ha sido llamado. |
| Interactive | 1 | El método [XmlReader::Read](../xmlreader/read/) ha sido llamado. Se pueden llamar métodos adicionales al lector. |
| Error | 2 | Se produjo un error que impide que la operación de lectura continúe. |
| EndOfFile | 3 | Se ha alcanzado el final del archivo con éxito. |
| Closed | 4 | El método [XmlReader::Close](../xmlreader/close/) ha sido llamado. |

## Ver también

* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)