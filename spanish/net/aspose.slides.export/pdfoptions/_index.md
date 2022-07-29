---
title: PdfOptions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato PDF.
type: docs
weight: 3930
url: /es/net/aspose.slides.export/pdfoptions/
---
## PdfOptions class

Proporciona opciones que controlan cómo se guarda una presentación en formato PDF.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfOptions](pdfoptions)() | Constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contiene un conjunto de indicadores que especifican qué permisos de acceso se deben otorgar cuando se abre el documento con acceso de usuario. Ver[`PdfAccessPermissions`](../pdfaccesspermissions) . |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Devuelve o establece una matriz de nombres definidos por el usuario de familias de fuentes que Aspose.Slides debería considerar comunes. Lectura/escrituraString []. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Aplica el color transparente especificado a una imagen si`verdadero` . |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indica si se debe seleccionar la compresión más efectiva (en lugar de la predeterminada) para cada imagen automáticamente. Si se establece enBoolean.true, para cada imagen en presentación se elegirá el algoritmo de compresión más apropiado, lo que conducirá al menor tamaño del documento PDF resultante.  La selección de la mejor relación de compresión de imagen es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción esBoolean.falso por defecto. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Nivel de conformidad deseado para el documento PDF generado. Lectura/escritura[`PdfCompliance`](../pdfcompliance) . |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Lectura-escrituraString . |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escrituraBoolean . |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Determina si se deben incrustar todos los caracteres de la fuente o solo se debe usar un subconjunto. Lectura/escrituraBoolean . |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de código 33..127). Las fuentes para códigos de caracteres superiores a 127 siempre están incrustadas. La lista de fuentes comunes incluye fuentes base 14 de PDF y fuentes adicionales especificadas por el usuario. Leer escribirBoolean . |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Obtiene o establece el color transparente de la imagen. |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escrituraByte . |
| [NotesCommentsLayouting](../../aspose.slides.export/pdfoptions/notescommentslayouting) { get; } | Proporciona opciones que controlan cómo se colocan las notas y los comentarios en el documento exportado. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Configuración de contraseña de usuario para proteger el documento PDF. Lectura/escrituraString . |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True para convertir todos los metarchivos utilizados en una presentación a imágenes PNG. Lectura/escrituraBoolean . |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es`falso` |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Especifica el tipo de compresión que se utilizará para todo el contenido textual del documento. Lectura/escritura[`PdfTextCompression`](../pdftextcompression) . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve de establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se cancelará. Lectura/escritura[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Ver también

* class [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
