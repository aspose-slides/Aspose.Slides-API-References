---
title: SVGOptions
second_title: Aspose.Sildes para la referencia de API de .NET
description: Representa una opción SVG.
type: docs
weight: 4430
url: /es/aspose.slides.export/svgoptions/
---
## clase SVGOptions

Representa una opción SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicializa una nueva instancia de la clase SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializa una nueva instancia de la clase SVGOptions especificando el objeto controlador de inserción de enlaces. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Devuelve la configuración predeterminada. Solo lectura [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Devuelve la configuración para la generación del archivo SVG más simple y pequeño. Solo lectura [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Devuelve la configuración para la generación del archivo SVG más preciso. Solo lectura [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente original. Lectura/escritura String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Una bandera boolean indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas se eliminarán; si es false se serializarán en el documento (lo que puede llevar a un archivo más grande). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Determina si el texto 3D está deshabilitado en SVG. Lectura/escritura Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Obtiene o establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Desactiva la división de los degradados FromCornerX y FromCenter. Lectura/escritura Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 no permite definir inserciones para marcadores. El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema: recorta el extremo de la línea con flecha, de modo que la línea no se superponga a los marcadores. Esta opción desactiva dicho comportamiento. Lectura/escritura Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Determina una forma de manejar fuentes cargadas externamente. Lectura/escritura [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Determina la calidad de codificación JPEG. Lectura/escritura Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Devuelve o establece el límite de resolución inferior para la rasterización de metafiles. Lectura/escritura Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Representa el nivel de compresión de imágenes |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Lectura/escritura [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Determina si se debe realizar la rotación especificada de la forma al renderizar o no. Lectura/escritura Boolean. El valor predeterminado es true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Determina si el marco de texto se incluirá en el área de renderizado o no. Lectura/escritura Boolean. El valor predeterminado es false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Determina si el texto en una diapositiva se guardará como gráficos. Lectura/escritura Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ver también

* clase [SaveOptions](../saveoptions)
* interfaz [ISVGOptions](../isvgoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->