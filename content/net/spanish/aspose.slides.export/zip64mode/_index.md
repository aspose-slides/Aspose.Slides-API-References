---
title: Zip64Mode
second_title: Referencia de API de Aspose.Sildes para .NET
description: Especifica cuándo usar extensiones del formato ZIP64 para archivos OpenXML.
type: docs
weight: 4550
url: /es/aspose.slides.export/zip64mode/
---

## Enumeración Zip64Mode

Especifica cuándo usar extensiones del formato ZIP64 para archivos OpenXML.

```csharp
public enum Zip64Mode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Nunca | `0` | No usar extensiones del formato ZIP64. |
| SiEsNecesario | `1` | Usar extensiones del formato ZIP64 si es necesario. |
| Siempre | `2` | Siempre usar extensiones del formato ZIP64. |

### Observaciones

El archivo OpenXML es un archivo ZIP que tiene un límite de 4 GB (2^32 bytes) en el tamaño no comprimido de un archivo, tamaño comprimido de un archivo y tamaño total del archivo, así como un límite de 65,535 (2^16-1) archivos en el archivo. Las extensiones del formato ZIP64 aumentan los límites a 2^64.

### Vea También

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->