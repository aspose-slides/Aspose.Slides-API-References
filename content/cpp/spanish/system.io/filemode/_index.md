---
title: FileMode
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica cómo debe abrirse un archivo.
type: docs
weight: 508
url: /es/system.io/filemode/
---
## FileMode enumeración


Especifica cómo debe abrirse un archivo.

```cpp
enum class FileMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| CreateNew | 1 | Crea un archivo nuevo. Si el archivo ya existe, se lanza una excepción. |
| Create | 2 | Crea un archivo nuevo. Si el archivo ya existe, se sobrescribe. |
| Open | 3 | Abre un archivo existente. Si el archivo no existe, se lanza una excepción. |
| OpenOrCreate | 4 | Abre un archivo existente o crea uno nuevo si no existe. |
| Truncate | 5 | Abre un archivo existente y lo trunca para que quede vacío. Si el archivo no existe, se lanza una excepción. |
| Append | 6 | Abre un archivo existente y se posiciona al final del mismo o crea uno nuevo si no existe. |

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)