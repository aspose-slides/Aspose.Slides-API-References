---
title: IPdfOptions class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/ipdfoptions/
---
## IPdfOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.

El tipo IPdfOptions expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`text_compression`](/slides/python-net/es/aspose.slides.export/ipdfoptions/text_compression/) | Especifica el tipo de compresión que se usará para todo el contenido textual del documento.<br/>            Lectura/escritura [`PdfTextCompression`](/slides/python-net/es/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/es/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Indica si se debe seleccionar automáticamente la compresión más eficaz (en lugar de la predeterminada) para cada imagen.<br/>            Si se establece en **bool**.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que producirá un tamaño menor del documento PDF resultante.<br/>            La selección de la mejor relación de compresión de imágenes es computacionalmente costosa y consume una cantidad adicional de RAM, y esta opción es **bool**.false por defecto. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/es/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Verdadero para incrustar fuentes TrueType para los caracteres ASCII 32-127.<br/>            Las fuentes para códigos de caracteres superiores a 127 siempre se incrustan.<br/>            Lectura/escritura **bool**. |
| [`show_hidden_slides`](/slides/python-net/es/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Especifica si el documento generado debe incluir diapositivas ocultas o no.<br/>            El valor predeterminado es `false`. |
| [`additional_common_font_families`](/slides/python-net/es/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes.<br/>            Lectura/escritura **str**[]. |
| [`embed_full_fonts`](/slides/python-net/es/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Determina si se deben incrustar todos los caracteres de la fuente o solo el subconjunto utilizado.<br/>            Lectura/escritura **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/es/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo negrita.<br/>            Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes.<br/>            Lectura/escritura **bool**. |
| [`jpeg_quality`](/slides/python-net/es/aspose.slides.export/ipdfoptions/jpeg_quality/) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.<br/>            Lectura/escritura **int**. |
| [`compliance`](/slides/python-net/es/aspose.slides.export/ipdfoptions/compliance/) | Nivel de conformidad deseado para el documento PDF generado.<br/>            Lectura/escritura [`PdfCompliance`](/slides/python-net/es/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/es/aspose.slides.export/ipdfoptions/password/) | Establece la contraseña de usuario para proteger el documento PDF.<br/>            Lectura/escritura **str**. |
| [`access_permissions`](/slides/python-net/es/aspose.slides.export/ipdfoptions/access_permissions/) | Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver [`PdfAccessPermissions`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/es/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Verdadero para convertir todos los metafiles utilizados en una presentación a imágenes PNG.<br/>            Lectura/escritura **bool**. |
| [`sufficient_resolution`](/slides/python-net/es/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF.<br/>            <br/>La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.<br/><br/><br/>El valor predeterminado es **96** .<br/><br/><br/>            Lectura/escritura **float**. |
| [`draw_slides_frame`](/slides/python-net/es/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Verdadero para dibujar un marco negro alrededor de cada diapositiva.<br/>             Lectura/escritura **bool**. |
| [`slides_layout_options`](/slides/python-net/es/aspose.slides.export/ipdfoptions/slides_layout_options/) | Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](/slides/python-net/es/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/es/aspose.slides.export/ipdfoptions/image_transparent_color/) | Obtiene o establece el color transparente de la imagen. |
| [`apply_image_transparent`](/slides/python-net/es/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Aplica el color transparente especificado a una imagen si `true`. |
| [`ink_options`](/slides/python-net/es/aspose.slides.export/ipdfoptions/ink_options/) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado.<br/>            Solo lectura [`IInkOptions`](/slides/python-net/es/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/es/aspose.slides.export/ipdfoptions/include_ole_data/) | Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante.<br/>            Lectura/escritura **bool**. |
| [`warning_callback`](/slides/python-net/es/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/es/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/es/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/es/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/es/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)