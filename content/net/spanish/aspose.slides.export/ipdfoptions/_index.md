---
title: IPdfOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.
type: docs
weight: 3830
url: /es/aspose.slides.export/ipdfoptions/
---

## Interfaz IPdfOptions

Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Contiene un conjunto de banderas que especifican qué permisos de acceso deben otorgarse cuando el documento se abre con acceso de usuario. Consulta [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Devuelve o establece un arreglo de nombres de familias de fuentes definidas por el usuario que Aspose.Slides debería considerar comunes. Lectura/escritura String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Aplica el color transparente especificado a una imagen si `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Indica si se debe seleccionar automáticamente la compresión más efectiva (en lugar de la predeterminada) para cada imagen. Si se establece en Boolean.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que dará lugar al tamaño más pequeño del documento PDF resultante. La selección de la mejor relación de compresión de imágenes es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción es Boolean.false de forma predeterminada. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Nivel de conformidad deseada para el documento PDF generado. Lectura/escritura [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Determina si se deben incrustar todos los caracteres de la fuente o solo el subconjunto utilizado. Lectura/escritura Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Verdadero para incrustar fuentes TrueType para caracteres ASCII 32-127. Las fuentes para códigos de caracteres mayores de 127 siempre se incrustan. Lectura/escritura Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Obtiene o establece el color transparente de la imagen. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos de tinta en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Establece la contraseña del usuario para proteger el documento PDF. Lectura/escritura String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilos en negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lectura/escritura Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Verdadero para convertir todos los metarchivos utilizados en una presentación a imágenes PNG. Lectura/escritura Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Especifica el tipo de compresión que se utilizará para todo el contenido textual en el documento. Lectura/escritura [`PdfTextCompression`](../pdftextcompression). |

### Ver También

* interfaz [ISaveOptions](../isaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->