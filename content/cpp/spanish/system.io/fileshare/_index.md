---
title: FileShare
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica qué tipo de acceso pueden tener otros objetos FileStream a un archivo que se está abriendo.
type: docs
weight: 534
url: /es/system.io/fileshare/
---
## FileShare enum

Especifica qué tipo de acceso pueden tener otros objetos [FileStream](../filestream/) a un archivo que se está abriendo.

```cpp
enum class FileShare
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Sin acceso. |
| Read | 1 | Acceso de solo lectura. |
| Write | 2 | Acceso de solo escritura. |
| ReadWrite | 3 | Acceso de lectura y escritura. |
| Delete | 4 | El archivo puede ser eliminado. |
| Inheritable | 16 | Hace que el manejador del archivo sea heredable por procesos hijos. |

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)