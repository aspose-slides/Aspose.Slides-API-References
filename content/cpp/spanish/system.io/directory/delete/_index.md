---
title: Delete()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina el archivo o directorio especificado. No lanza una excepción.
type: docs
weight: 14
url: /es/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) método

Elimina el archivo o directorio especificado. No lanza una excepción.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta al directorio o archivo que se eliminará |
| recursive | **bool** | Si **path** especifica un directorio que no está vacío, entonces **recursive** indica si todo el contenido del directorio debe eliminarse de forma recursiva; si el directorio especificado por **path** no está vacío y **recursive** es 'false', la operación falla |

## Ver también

* Clase [String](../../../system/string/)
* Clase [Directory](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)