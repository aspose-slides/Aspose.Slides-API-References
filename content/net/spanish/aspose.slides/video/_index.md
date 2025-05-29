---
title: Video
second_title: Referencia de la API Aspose.Sildes para .NET
description: Representa una imagen incrustada en una presentación.
type: docs
weight: 11390
url: /es/aspose.slides/video/
---

## Clase Video

Representa una imagen incrustada en una presentación.

```csharp
public class Video : IVideo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BinaryData](../../aspose.slides/video/binarydata) { get; } | Devuelve una copia de los datos de un audio. En caso de grandes cantidades de datos, considere usar el método [`GetStream`](./getstream) para evitar cargar innecesariamente los datos del video en la memoria o incluso provocar OutOfMemoryException. Solo lectura Byte[]. |
| [ContentType](../../aspose.slides/video/contenttype) { get; } | Devuelve un tipo MIME de un video, codificado en [`BinaryData`](./binarydata). Solo lectura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetStream](../../aspose.slides/video/getstream)() | Devuelve un Stream para lectura. Use 'using' o cierre el stream después de usarlo. |

### Véase también

* interfaz [IVideo](../ivideo)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->