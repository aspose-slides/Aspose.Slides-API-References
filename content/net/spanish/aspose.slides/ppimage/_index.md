---
title: PPImage
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa una imagen en una presentación.
type: docs
weight: 8980
url: /es/aspose.slides/ppimage/
---

## Clase PPImage

Representa una imagen en una presentación.

```csharp
public class PPImage : IDisposable, IPPImage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BinaryData](../../aspose.slides/ppimage/binarydata) { get; } | Devuelve la copia de los datos de una imagen. Solo lectura Byte[]. |
| [ContentType](../../aspose.slides/ppimage/contenttype) { get; } | Devuelve un tipo MIME de una imagen, codificado en [`BinaryData`](./binarydata). Solo lectura String. |
| [Height](../../aspose.slides/ppimage/height) { get; } | Devuelve una altura de una imagen. Solo lectura Int32. |
| [Image](../../aspose.slides/ppimage/image) { get; } | Devuelve la copia de una imagen. Solo lectura [`IImage`](../iimage). |
| [SvgImage](../../aspose.slides/ppimage/svgimage) { get; set; } | Devuelve u establece el objeto ISvgImage [`ISvgImage`](../isvgimage) |
| [Width](../../aspose.slides/ppimage/width) { get; } | Devuelve un ancho de una imagen. Solo lectura Int32. |
| [X](../../aspose.slides/ppimage/x) { get; } | Devuelve un desplazamiento X de una imagen. Solo lectura Int32. |
| [Y](../../aspose.slides/ppimage/y) { get; } | Devuelve un desplazamiento Y de una imagen. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.slides/ppimage/dispose)() | Libera el objeto. |
| override [GetHashCode](../../aspose.slides/ppimage/gethashcode)() | Devuelve el código hash de una imagen. |
| [ReplaceImage](../../aspose.slides/ppimage/replaceimage#replaceimage_2)(byte[]) | Reemplaza los datos de la imagen. Los datos de la nueva imagen. Cuando el parámetro newImageData es nulo. |
| [ReplaceImage](../../aspose.slides/ppimage/replaceimage#replaceimage)(IImage) | Reemplaza los datos de la imagen. Atención: cuando la imagen es un metafile - será rasterizada. Use ReplaceImage(byte[]) en su lugar. La nueva imagen. Cuando el parámetro newImage es nulo. |
| [ReplaceImage](../../aspose.slides/ppimage/replaceimage#replaceimage_1)(IPPImage) | Reemplaza los datos de la imagen. La nueva IPPImage. Cuando el parámetro newImage es nulo. |

### Véase también

* interfaz [IPPImage](../ippimage)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->