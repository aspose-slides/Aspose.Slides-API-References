---
title: Replace()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto FileInfo actual y crea una copia de seguridad del archivo reemplazado.
type: docs
weight: 131
url: /es/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) método

Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](../) actual y crea una copia de seguridad del archivo reemplazado.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Un nombre del archivo a reemplazar |
| destinationBackupFileName | const [String](../../../system/string/)\& | Un nombre del archivo de copia de seguridad |

### Valor de retorno

Un objeto FileInfor que representa el archivo al que apunta **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) método

Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](../) actual y crea una copia de seguridad del archivo reemplazado.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Un nombre del archivo a reemplazar |
| destinationBackupFileName | const [String](../../../system/string/)\& | Un nombre del archivo de copia de seguridad |
| ignoreMetadataErrors | **bool** | Especifica si los errores de fusión del archivo reemplazado al archivo de sustitución deben ser ignorados (true) o no (false) |

### Valor de retorno

Un objeto FileInfor que representa el archivo al que apunta **destinationFileName**

## Ver también

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Clase [String](../../../system/string/)
* Clase [FileInfo](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)