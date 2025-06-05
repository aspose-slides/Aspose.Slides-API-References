---  
title: SVGOptions
second_title: Referencia de API de Aspose.Slides para .NET  
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
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializa una nueva instancia de la clase SVGOptions especificando el objeto controlador de incrustación de enlace. |  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Devuelve la configuración predeterminada. Solo lectura [`SVGOptions`](../svgoptions). |  
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Devuelve la configuración para la generación de archivos SVG más simple y pequeño. Solo lectura [`SVGOptions`](../svgoptions). |  
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Devuelve la configuración para la generación de archivos SVG más precisa. Solo lectura [`SVGOptions`](../svgoptions). |  
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Lectura/escritura String. |  
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Un indicador booleano que indica si las partes recortadas permanecen como parte del documento. Si es verdadero, las partes recortadas se eliminarán; si es falso, se serializarán en el documento (lo que puede llevar a un archivo más grande). |  
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Determina si el texto 3D está deshabilitado en SVG. Lectura/escritura Boolean. |  
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Obtiene o establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en `true`, las ligaduras se deshabilitarán en la salida renderizada. Por defecto, esta propiedad se establece en `false`. |  
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Deshabilita la división de gradientes FromCornerX y FromCenter. Lectura/escritura Boolean. |  
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 carece de la capacidad para definir márgenes para los marcadores. El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema: recorta el extremo de la línea con una flecha, por lo que la línea no se superpone a los marcadores. Esta opción desactiva tal comportamiento. Lectura/escritura Boolean. |  
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Determina una forma de manejar fuentes cargadas externamente. Lectura/escritura [`SvgExternalFontsHandling`](../svgexternalfontshandling). |  
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del gradiente. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |  
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos de tinta en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |  
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Determina la calidad de codificación JPEG. Lectura/escritura Int32. |  
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Devuelve o establece el límite de resolución más bajo para la rasterización de metarchivos. Lectura/escritura Int32. |  
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Representa el nivel de compresión de las imágenes |  
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de callback para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |  
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Devuelve y establece una interfaz de callback que permite al usuario controlar la conversión de formas. Lectura/escritura [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |  
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hiperenlaces con llamadas de JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |  
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Determina si se debe realizar la rotación especificada de la forma al renderizar o no. Lectura/escritura Boolean. El valor predeterminado es verdadero. |  
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Determina si el marco de texto se incluirá en un área de renderizado o no. Lectura/escritura Boolean. El valor predeterminado es falso. |  
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Determina si el texto en una diapositiva se guardará como gráficos. Lectura/escritura Boolean. |  
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |  

### Ver También  

* clase [SaveOptions](../saveoptions)  
* interfaz [ISVGOptions](../isvgoptions)  
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)  
* ensamblaje [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  