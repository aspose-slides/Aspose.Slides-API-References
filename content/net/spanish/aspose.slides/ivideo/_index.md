---
title: IVideo
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un video incrustado en una presentación.
type: docs
weight: 7140
url: /es/aspose.slides/ivideo/
---

## Interfaz IVideo

Representa un video incrustado en una presentación.

```csharp
public interface IVideo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BinaryData](../../aspose.slides/ivideo/binarydata) { get; } | Devuelve la copia de los datos de un audio. En caso de gran cantidad de datos, considere utilizar el método [`GetStream`](./getstream) para prevenir la carga innecesaria de los datos del video en la memoria o incluso OutOfMemoryException. Solo de lectura Byte[]. |
| [ContentType](../../aspose.slides/ivideo/contenttype) { get; } | Devuelve un tipo MIME de un video, codificado en [`BinaryData`](./binarydata). Solo de lectura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetStream](../../aspose.slides/ivideo/getstream)() | Devuelve un Stream para lectura. Use 'using' o cierre el stream después de usarlo. |

### Véase También

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->