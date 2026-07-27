---
title: CopyTo()
second_title: Referencia de API de Aspose.Slides para C++
description: Copia el archivo representado por el objeto actual a la ubicación especificada. Si el archivo de destino ya existe, la copia falla.
type: docs
weight: 105
url: /es/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) método

Copia el archivo representado por el objeto actual a la ubicación especificada. Si el archivo de destino ya existe, la copia falla.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | El nombre del archivo de destino |

### Valor de retorno

Un objeto [FileInfo](../) que representa la copia

## FileInfo::CopyTo(const String\&, bool) método

Copia el archivo representado por el objeto actual a la ubicación especificada. Un parámetro indica si el archivo de destino existente debe sobrescribirse.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | El nombre del archivo de destino |
| overwrite | **bool** | True si el archivo de destino existente debe sobrescribirse, false si la copia debe fallar si el archivo de destino ya existe |

### Valor de retorno

Un objeto [FileInfo](../) que representa la copia

## Ver también

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Clase [String](../../../system/string/)
* Clase [FileInfo](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)