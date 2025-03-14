---
title: ISVGOptions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una opción de SVG.
type: docs
weight: 3730
url: /es/aspose.slides.export/isvgoptions/
---
## ISVGOptions interface

Representa una opción de SVG.

```csharp
public interface ISVGOptions : ISaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/isvgoptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura[`ISaveOptions`](../isaveoptions) . |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/isvgoptions/deletepicturescroppedareas) { get; set; } | Un indicador booleano indica si las partes recortadas permanecen como parte del documento. Si es verdadero, las partes recortadas se eliminarán, si es falso, se serializarán en el documento (lo que puede generar un archivo más grande) Lectura/escrituraBoolean . |
| [Disable3DText](../../aspose.slides.export/isvgoptions/disable3dtext) { get; set; } | Determina si el texto 3D está deshabilitado en SVG. Lectura/escrituraBoolean . |
| [DisableGradientSplit](../../aspose.slides.export/isvgoptions/disablegradientsplit) { get; set; } | Desactiva la división de gradientes FromCornerX y FromCenter. Lectura/escrituraBoolean . |
| [DisableLineEndCropping](../../aspose.slides.export/isvgoptions/disablelineendcropping) { get; set; } | SVG 1.1 no tiene la capacidad de definir inserciones para marcadores. El motor de escritura Aspose.Slides SVG tiene una solución para ese problema: recorta el final de la línea con la flecha, por lo que la línea no se superpone a los marcadores. Esta opción desactiva dicho comportamiento. Lectura/escrituraBoolean . |
| [ExternalFontsHandling](../../aspose.slides.export/isvgoptions/externalfontshandling) { get; set; } | Determina una forma de manejar las fuentes cargadas externamente. Lectura/escritura[`SvgExternalFontsHandling`](../svgexternalfontshandling) . |
| [JpegQuality](../../aspose.slides.export/isvgoptions/jpegquality) { get; set; } | Determina la calidad de la codificación JPEG. Lectura/escrituraInt32 . |
| [MetafileRasterizationDpi](../../aspose.slides.export/isvgoptions/metafilerasterizationdpi) { get; set; } | Devuelve o establece el límite de resolución inferior para la rasterización de metarchivos. Lectura/escrituraInt32 . |
| [PicturesCompression](../../aspose.slides.export/isvgoptions/picturescompression) { get; set; } | Representa el nivel de compresión de las imágenes Lectura/escritura[`PicturesCompression`](./picturescompression) . |
| [ShapeFormattingController](../../aspose.slides.export/isvgoptions/shapeformattingcontroller) { get; set; } | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Lectura/escritura[`ISvgShapeFormattingController`](../isvgshapeformattingcontroller) . |
| [VectorizeText](../../aspose.slides.export/isvgoptions/vectorizetext) { get; set; } | Determina si el texto de una diapositiva se guardará como gráficos. Lectura/escrituraBoolean . |

### Ver también

* interface [ISaveOptions](../isaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
