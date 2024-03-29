---
title: IPdfOptions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato PDF.
type: docs
weight: 3680
url: /es/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interface

Proporciona opciones que controlan cómo se guarda una presentación en formato PDF.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Contiene un conjunto de indicadores que especifican qué permisos de acceso se deben otorgar cuando se abre el documento con acceso de usuario. Ver[`PdfAccessPermissions`](../pdfaccesspermissions) . |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Devuelve o establece una matriz de nombres definidos por el usuario de familias de fuentes que Aspose.Slides debería considerar comunes. Lectura/escrituraString []. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Aplica el color transparente especificado a una imagen si`verdadero` . |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura[`ISaveOptions`](../isaveoptions) . |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Indica si se debe seleccionar la compresión más efectiva (en lugar de la predeterminada) para cada imagen automáticamente. Si se establece enBoolean.true, para cada imagen en presentación se elegirá el algoritmo de compresión más apropiado, lo que conducirá al menor tamaño del documento PDF resultante.  La selección de la mejor relación de compresión de imagen es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción esBoolean.falso por defecto. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Nivel de conformidad deseado para el documento PDF generado. Lectura/escritura[`PdfCompliance`](../pdfcompliance) . |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escrituraBoolean . |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Determina si se deben incrustar todos los caracteres de la fuente o solo se debe usar un subconjunto. Lectura/escrituraBoolean . |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True para incrustar fuentes true type para caracteres ASCII 32-127. Las fuentes para códigos de caracteres mayores de 127 siempre están incrustadas. Lectura/escrituraBoolean . |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Obtiene o establece el color transparente de la imagen. |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escrituraByte . |
| [NotesCommentsLayouting](../../aspose.slides.export/ipdfoptions/notescommentslayouting) { get; } | Proporciona opciones que controlan cómo se colocan las notas y los comentarios en el documento exportado. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Configuración de contraseña de usuario para proteger el documento PDF. Lectura/escrituraString . |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True para convertir todos los metarchivos utilizados en una presentación a imágenes PNG. Lectura/escrituraBoolean . |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es`falso` |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Especifica el tipo de compresión que se utilizará para todo el contenido textual del documento. Lectura/escritura[`PdfTextCompression`](../pdftextcompression) . |

### Ver también

* interface [ISaveOptions](../isaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
