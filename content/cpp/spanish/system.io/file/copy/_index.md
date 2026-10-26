---
title: Copy()
second_title: Referencia de API de Aspose.Slides para C++
description: Copia el archivo especificado a la ubicación especificada. Si el archivo de destino ya existe, un parámetro indica si debe sobrescribirse.
type: docs
weight: 40
url: /es/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) método


Copia el archivo especificado a la ubicación especificada. Si el archivo de destino ya existe, un parámetro indica si debe sobrescribirse.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Una ruta del archivo a copiar |
| destFileName | const [String](../../../system/string/)\& | Una ruta de la nueva ubicación del archivo a copiar |
| overwrite | **bool** | True si el archivo de destino existente debe sobrescribirse, false si la copia debe fallar si el archivo de destino ya existe |

## Ver también

* Clase [String](../../../system/string/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)