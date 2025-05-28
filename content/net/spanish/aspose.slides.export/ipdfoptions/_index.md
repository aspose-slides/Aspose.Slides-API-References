---
title: IPdfOptions
second_title: Aspose.Slides para referencia de API de .NET
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
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Contiene un conjunto de flags que especifican qué permisos de acceso deben ser concedidos cuando el documento se abre con acceso de usuario. Vea [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Devuelve o establece un array de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. Lee/escribe String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Aplica el color transparente especificado a una imagen si `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Indica si se debe seleccionar automáticamente la compresión más efectiva (en lugar de la predeterminada) para cada imagen. Si se establece en Boolean.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que dará como resultado un tamaño más pequeño del documento PDF resultante. La selección de la mejor tasa de compresión de imagen es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción es Boolean.false por defecto. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Nivel de conformidad deseado para el documento PDF generado. Lee/escribe [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lee/escribe Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Determina si todos los caracteres de la fuente deben ser incrustados o solo el subconjunto utilizado. Lee/escribe Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Verdadero para incrustar fuentes TrueType para caracteres ASCII 32-127. Las fuentes para códigos de carácter mayores que 127 siempre se incrustan. Lee/escribe Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Obtiene o establece el color transparente de la imagen. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Verdadero para convertir todos los datos OLE de la presentación a archivos incrustados en el PDF resultante. Lee/escribe Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos de tinta en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lee/escribe Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Establece una contraseña de usuario para proteger el documento PDF. Lee/escribe String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica si el texto debe ser rasterizado como un bitmap y guardado en PDF cuando la fuente no admite estilos en negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lee/escribe Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Verdadero para convertir todos los metafiles utilizados en una presentación en imágenes PNG. Lee/escribe Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Especifica el tipo de compresión que se utilizará para todo el contenido textual en el documento. Lee/escribe [`PdfTextCompression`](../pdftextcompression). |

### Consulta También

* interfaz [ISaveOptions](../isaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->