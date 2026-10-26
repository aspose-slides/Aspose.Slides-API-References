---
title: PdfOptions class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/pdfoptions/
---
## PdfOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.

**Herencia:**[`PdfOptions`](/slides/python-net/es/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)

El tipo PdfOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.export/pdfoptions/__init__/#) | Constructor predeterminado. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/pdfoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/pdfoptions/progress_callback/) | Representa un objeto de devolución de llamada para actualizaciones del progreso de guardado en porcentaje.<br/>            Ver [`IProgressCallback`](/slides/python-net/es/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/pdfoptions/default_regular_font/) | Devuelve o establece la fuente utilizada en caso de que la fuente origen no se encuentre.<br/>            Lectura-escritura **str**. |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/pdfoptions/gradient_style/) | Devuelve o establece el estilo visual del degradado.<br/>            Lectura/escritura [`GradientStyle`](/slides/python-net/es/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/pdfoptions/skip_java_script_links/) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. <br/>            Lectura/escritura **bool**. El valor predeterminado es **false** . |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/pdfoptions/slides_layout_options/) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/pdfoptions/ink_options/) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado.<br/>            Sólo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/pdfoptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`text_compression`](/slides/python-net/es/aspose.slides.export/pdfoptions/text_compression/) | Especifica el tipo de compresión que se usará para todo el contenido textual en el documento.<br/>            Lectura/escritura [`PdfTextCompression`](/slides/python-net/es/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/es/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente<br/>            Si se establece en **bool**.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que producirá un tamaño menor del documento PDF resultante.<br/>            La selección de la mejor relación de compresión de imágenes es computacionalmente costosa y consume una cantidad adicional de RAM, y esta opción es **bool**.false por defecto. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/es/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de códigos 33..127).<br/>            Las fuentes para códigos de caracteres mayores a 127 siempre se incrustan.<br/>            La lista de fuentes comunes incluye las 14 fuentes base de PDF y fuentes adicionales especificadas por el usuario.<br/>            Lectura/escritura **bool**. |
| [`additional_common_font_families`](/slides/python-net/es/aspose.slides.export/pdfoptions/additional_common_font_families/) | Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes.<br/>            Lectura/escritura **str**[]. |
| [`embed_full_fonts`](/slides/python-net/es/aspose.slides.export/pdfoptions/embed_full_fonts/) | Determina si todos los caracteres de la fuente deben incrustarse o solo el subconjunto utilizado.<br/>            Lectura/escritura **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/es/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo en negrita.<br/>            Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes.<br/>            Lectura/escritura **bool**. |
| [`jpeg_quality`](/slides/python-net/es/aspose.slides.export/pdfoptions/jpeg_quality/) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.<br/>            Lectura/escritura **int**. |
| [`compliance`](/slides/python-net/es/aspose.slides.export/pdfoptions/compliance/) | Nivel de conformidad deseado para el documento PDF generado.<br/>            Lectura/escritura [`PdfCompliance`](/slides/python-net/es/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/es/aspose.slides.export/pdfoptions/password/) | Estableciendo la contraseña de usuario para proteger el documento PDF. <br/>            Lectura/escritura **str**. |
| [`access_permissions`](/slides/python-net/es/aspose.slides.export/pdfoptions/access_permissions/) | Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario.<br/>            Ver [`PdfAccessPermissions`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/es/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | True para convertir todos los metafiles usados en una presentación a imágenes PNG.<br/>            Lectura/escritura **bool**. |
| [`sufficient_resolution`](/slides/python-net/es/aspose.slides.export/pdfoptions/sufficient_resolution/) | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF.<br/>            <br/>La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.<br/><br/><br/>El valor predeterminado es **96** .<br/><br/><br/>            Lectura/escritura **float**. |
| [`draw_slides_frame`](/slides/python-net/es/aspose.slides.export/pdfoptions/draw_slides_frame/) | True para dibujar un marco negro alrededor de cada diapositiva.<br/>             Lectura/escritura **bool**. |
| [`image_transparent_color`](/slides/python-net/es/aspose.slides.export/pdfoptions/image_transparent_color/) | Obtiene o establece el color transparente de la imagen. |
| [`apply_image_transparent`](/slides/python-net/es/aspose.slides.export/pdfoptions/apply_image_transparent/) | Aplica el color transparente especificado a una imagen si `true`. |
| [`include_ole_data`](/slides/python-net/es/aspose.slides.export/pdfoptions/include_ole_data/) | True para convertir todos los datos OLE de la presentación a archivos incrustados en el PDF resultante.<br/>            Lectura/escritura **bool**. |

### Ver también
* clase [`PdfOptions`](/slides/python-net/es/aspose.slides.export/pdfoptions)
* clase [`SaveOptions`](/slides/python-net/es/aspose.slides.export/saveoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)