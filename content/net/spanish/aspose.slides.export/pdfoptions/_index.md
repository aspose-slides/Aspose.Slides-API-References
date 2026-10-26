---
title: PdfOptions
second_title: Referencia de API de Aspose.Sildes para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.
type: docs
weight: 4330
url: /es/aspose.slides.export/pdfoptions/
---
## PdfOptions clase

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Devuelve o establece una matriz de nombres de familias de fuentes definidas por el usuario que Aspose.Slides debe considerar comunes. Lectura/escritura String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Aplica el color transparente especificado a una imagen si `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en Boolean.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que producirá un tamaño menor del documento PDF resultante. La selección de la mejor relación de compresión de imágenes es costosa computacionalmente y requiere una cantidad adicional de RAM, y esta opción es Boolean.false por defecto. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Nivel de conformidad deseado para el documento PDF generado. Lectura/escritura [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que la fuente original no se encuentre. Lectura/escritura String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Determina si se deben incrustar todos los caracteres de la fuente o solo el subconjunto utilizado. Lectura/escritura Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). Las fuentes para códigos de caracteres superiores a 127 siempre se incrustan. La lista de fuentes comunes incluye las 14 fuentes base de PDF y fuentes adicionales especificadas por el usuario. Lectura/escritura Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Obtiene o establece el color transparente de la imagen. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Establece la contraseña de usuario para proteger el documento PDF. Lectura/escritura String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo en negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lectura/escritura Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Lectura/escritura Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Especifica el tipo de compresión que se usará para todo el contenido textual del documento. Lectura/escritura [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con opciones personalizadas.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancia la clase PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Establece la calidad Jpeg
	pdfOptions.JpegQuality = 90;
	// Establece el comportamiento de los metafiles
	pdfOptions.SaveMetafilesAsPng = true;
	// Establece el nivel de compresión de texto
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Define la norma PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Guarda la presentación como PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con diapositivas ocultas.

```csharp
[C#]
// Instancia una clase Presentation que representa un archivo PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancia la clase PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Añade diapositivas ocultas
	pdfOptions.ShowHiddenSlides = true;
	// Guarda la presentación como PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a PDF protegido con contraseña.

```csharp
[C#]
// Instancia un objeto Presentation que representa un archivo PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instancia la clase PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Establece la contraseña PDF y los permisos de acceso
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Guarda la presentación como PDF
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
		// Estableciendo el tipo y tamaño de la diapositiva
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Ver también

* clase [SaveOptions](../saveoptions)
* interfaz [IPdfOptions](../ipdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->