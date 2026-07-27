---
title: FileOptions
second_title: Referencia de API de Aspose.Slides para C++
description: Representa opciones avanzadas para crear el objeto FileStream.
type: docs
weight: 521
url: /es/system.io/fileoptions/
---
## FileOptions enumeración


Representa opciones avanzadas para crear el objeto [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Sin opciones adicionales. |
| Encrypted | 16384 | El archivo está encriptado. NOT IMPLEMENTED. |
| DeleteOnClose | 67108864 | El archivo debe eliminarse automáticamente cuando ya no esté en uso. |
| SequentialScan | 134217728 | El archivo debe accederse secuencialmente. |
| RandomAccess | 268435456 | El archivo se accede de forma aleatoria. |
| Asynchronous | 1073741824 | El archivo puede usarse para operaciones de E/S asíncronas. |
| WriteThrough | n/a | Todas las escrituras deben ir directamente al disco, evitando cualquier caché intermedia. |

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)