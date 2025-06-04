---
title: IVideo
second_title: Aspose.Slides para .NET Referencia de API
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
| [BinaryData](../../aspose.slides/ivideo/binarydata) { get; } | Devuelve la copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el método [`GetStream`](./getstream) para prevenir la carga innecesaria de los datos del video en la memoria o incluso excepciones de OutOfMemory. Solo lectura Byte[]. |
| [ContentType](../../aspose.slides/ivideo/contenttype) { get; } | Devuelve un tipo MIME de un video, codificado en [`BinaryData`](./binarydata). Solo lectura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetStream](../../aspose.slides/ivideo/getstream)() | Devuelve un Stream para lectura. Use 'using' o cierre el stream después de usarlo. |

### Ver También

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->