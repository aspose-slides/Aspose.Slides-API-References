---
title: SVGOptions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una opción SVG.
type: docs
weight: 4240
url: /es/aspose.slides.export/svgoptions/
---

## Clase SVGOptions

Representa una opción SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicializa una nueva instancia de la clase SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializa una nueva instancia de la clase SVGOptions especificando el objeto controlador de enlace. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Devuelve la configuración predeterminada. Solo lectura [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Devuelve la configuración para la generación de archivos SVG más simples y pequeños. Solo lectura [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Devuelve la configuración para la generación de archivos SVG más precisos. Solo lectura [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Un indicador booleano que indica si las partes recortadas permanecen como parte del documento. Si es verdadero, las partes recortadas se eliminarán; si es falso, se serializarán en el documento (lo que puede llevar a un archivo más grande) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Determina si el texto 3D está deshabilitado en SVG. Booleano de lectura/escritura. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en `true`, las ligaduras se deshabilitarán en la salida renderizada. Por defecto, esta propiedad se establece en `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Deshabilita la división de gradientes FromCornerX y FromCenter. Booleano de lectura/escritura. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 carece de la capacidad de definir inserciones para indicadores. El motor de escritura SVG de Aspose.Slides tiene una solución para ese problema: recorta el final de la línea con la flecha, por lo que la línea no se superpone a los indicadores. Esta opción desactiva dicho comportamiento. Booleano de lectura/escritura. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Determina la forma de manejar las fuentes cargadas externamente. Lectura/escritura [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del gradiente. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos de tinta en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Determina la calidad de codificación JPEG. Lectura/escritura Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Devuelve o establece el límite inferior de resolución para la rasterización de metarchivos. Lectura/escritura Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Representa el nivel de compresión de las imágenes |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de callback para actualizar el progreso de guardado en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Devuelve y establece una interfaz de callback que permite al usuario controlar la conversión de formas. Lectura/escritura [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hiperenlaces con llamadas de JavaScript al guardar la presentación. Booleano de lectura/escritura. El valor predeterminado es **falso**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Determina si se debe realizar la rotación especificada de la forma al renderizar o no. Booleano de lectura/escritura. El valor predeterminado es verdadero. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Determina si el marco de texto se incluirá en un área de renderizado o no. Booleano de lectura/escritura. El valor predeterminado es falso. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Determina si el texto en una diapositiva se guardará como gráficos. Booleano de lectura/escritura. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Véase también

* clase [SaveOptions](../saveoptions)
* interfaz [ISVGOptions](../isvgoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->