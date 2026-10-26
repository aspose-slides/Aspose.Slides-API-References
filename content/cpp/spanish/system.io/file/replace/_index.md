---
title: Replace()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplaza el contenido de un archivo con otro y crea una copia de seguridad del archivo reemplazado.
type: docs
weight: 339
url: /es/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) método

Reemplaza el contenido de un archivo con otro y crea una copia de seguridad del archivo reemplazado.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Un nombre del archivo con el que reemplazar |
| destinationFileName | const [String](../../../system/string/)\& | Un nombre del archivo a reemplazar |
| destinationBackupFileName | const [String](../../../system/string/)\& | Un nombre del archivo de copia de seguridad |
| ignoreMetadataErrors | **bool** | Especifica si los errores de fusión del archivo reemplazado al archivo de reemplazo deben ser ignorados (true) o no (false) |

## Ver también

* Clase [String](../../../system/string/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)