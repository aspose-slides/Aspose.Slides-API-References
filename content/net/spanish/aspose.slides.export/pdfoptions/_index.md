---
title: PdfOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.
type: docs
weight: 4140
url: /es/aspose.slides.export/pdfoptions/
---

## Clase PdfOptions

Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfOptions](pdfoptions)() | Constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contiene un conjunto de flags que especifican qué permisos de acceso deben otorgarse cuando se abre el documento con acceso de usuario. Ver [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Devuelve o establece un arreglo de nombres de familias de fuentes definidas por el usuario que Aspose.Slides debe considerar comunes. Lectura/escritura String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Aplica el color transparente especificado a una imagen si `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indica si se debe seleccionar automáticamente la compresión más efectiva (en lugar de la predeterminada) para cada imagen. Si se establece en Boolean.true, se elegirá el algoritmo de compresión más apropiado para cada imagen en la presentación, lo que llevará a un tamaño más pequeño del documento PDF resultante. La selección de la mejor relación de compresión de imágenes es costosa computacionalmente y requiere una cantidad adicional de RAM, y esta opción es Boolean.false de forma predeterminada. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Nivel de conformidad deseado para el documento PDF generado. Lectura/escritura [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Determina si todos los caracteres de la fuente deben ser incrustados o solo el subconjunto utilizado. Lectura/escritura Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). Las fuentes para códigos de caracteres mayores a 127 siempre se incrustan. La lista de fuentes comunes incluye las 14 fuentes base de PDF y fuentes adicionales especificadas por el usuario. Lectura/escritura Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Obtiene o establece el color transparente de la imagen. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos de tinta en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Establece la contraseña del usuario para proteger el documento PDF. Lectura/escritura String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para las actualizaciones de progreso de guardado en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica si el texto debe ser rasterizado como un mapa de bits y guardado en PDF cuando la fuente no admite el estilo negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lectura/escritura Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Verdadero para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Lectura/escritura Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hiperenlaces con llamadas de JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Especifica el tipo de compresión que se utilizará para todo el contenido textual en el documento. Lectura/escritura [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con opciones personalizadas.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancia la clase PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Establece la calidad de JPEG
	pdfOptions.JpegQuality = 90;
	// Establece el comportamiento para los metafiles
	pdfOptions.SaveMetafilesAsPng = true;
	// Establece el nivel de compresión de texto
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Define el estándar de PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Guarda la presentación como un PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con diapositivas ocultas.

```csharp
[C#]
// Instancia una clase Presentation que representa un archivo de PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancia la clase PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Agrega diapositivas ocultas
	pdfOptions.ShowHiddenSlides = true;
	// Guarda la presentación como un PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a PDF protegido por contraseña.

```csharp
[C#]
// Instancia un objeto Presentation que representa un archivo de PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancia la clase PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Establece la contraseña PDF y los permisos de acceso
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Guarda la presentación como un PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con notas.

```csharp
[C#]
// Instancia un objeto Presentation que representa un archivo de presentación
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Estableciendo el tipo y tamaño de diapositiva
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Véase También

* clase [SaveOptions](../saveoptions)
* interfaz [IPdfOptions](../ipdfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->