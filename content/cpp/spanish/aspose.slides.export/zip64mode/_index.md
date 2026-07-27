---
title: Zip64Mode
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica cuándo usar extensiones de formato ZIP64 para el archivo OpenXML.
type: docs
weight: 1119
url: /es/aspose.slides.export/zip64mode/
---
## Zip64Mode enum

Especifica cuándo usar extensiones de formato ZIP64 para el archivo OpenXML.

```cpp
enum class Zip64Mode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Never | 0 | No usar extensiones de formato ZIP64. |
| IfNecessary | 1 | Usar extensiones de formato ZIP64 si es necesario. |
| Always | 2 | Usar siempre extensiones de formato ZIP64. |

## Observaciones

El archivo OpenXML es un archivo ZIP que tiene un límite de 4 GB (2^32 bytes) en el tamaño sin comprimir de un archivo, el tamaño comprimido de un archivo y el tamaño total del archivo, así como un límite de 65,535 (2^16-1) archivos en el archivo. Las extensiones de formato ZIP64 aumentan los límites a 2^64.

## Ver también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)