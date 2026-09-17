---
title: ISlide class
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides/islide/
---
## ISlide clase

Representa una diapositiva en una presentación.

El tipo ISlide expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/islide/header_footer_manager/) | Devuelve el administrador HeaderFooter de la diapositiva.<br/>            Solo lectura [`ISlideHeaderFooterManager`](/slides/python-net/es/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/es/aspose.slides/islide/slide_number/) | Devuelve un número de diapositiva.<br/>            El índice de la diapositiva en la colección [`IPresentation.slides`](/slides/python-net/es/aspose.slides/ipresentation/slides) siempre es igual a SlideNumber - 1.<br/>            Lectura/escritura **int**. |
| [`hidden`](/slides/python-net/es/aspose.slides/islide/hidden/) | Determina si la diapositiva especificada está oculta durante una presentación.<br/>            Lectura/escritura **bool**. |
| [`layout_slide`](/slides/python-net/es/aspose.slides/islide/layout_slide/) | Devuelve o establece la diapositiva de diseño para la diapositiva actual.<br/>            Lectura/escritura [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/es/aspose.slides/islide/notes_slide_manager/) | Permite acceder a la diapositiva de notas, agregarla y eliminarla.<br/>            Solo lectura [`INotesSlideManager`](/slides/python-net/es/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/es/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/es/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/es/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/es/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/es/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/es/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/es/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/es/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/es/aspose.slides/islide/theme_manager/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/islide/get_image/#float-float) | Devuelve un objeto de imagen con escalado personalizado. |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/islide/get_image/#) | Devuelve un objeto de imagen Miniatura (20 % del tamaño real). |
| [`get_image(self, image_size)`](/slides/python-net/es/aspose.slides/islide/get_image/#asposepydrawingsize) | Devuelve un objeto de imagen con el tamaño especificado. |
| [`get_image(self, options)`](/slides/python-net/es/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Devuelve un objeto bitmap TIFF Miniatura con los parámetros especificados. |
| [`get_image(self, options)`](/slides/python-net/es/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Devuelve un objeto Bitmap Miniatura. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Devuelve un objeto Bitmap Miniatura con escalado personalizado. |
| [`get_image(self, options, image_size)`](/slides/python-net/es/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Devuelve un objeto Bitmap Miniatura con el tamaño especificado. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/islide/write_as_svg/#iorawiobase) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/es/aspose.slides/islide/get_slide_comments/#icommentauthor) | Devuelve todos los comentarios de la diapositiva añadidos por un autor específico. |
| [`write_as_emf(self, stream)`](/slides/python-net/es/aspose.slides/islide/write_as_emf/#iorawiobase) | Guarda el contenido de la diapositiva como un archivo EMF. |
| [`remove(self)`](/slides/python-net/es/aspose.slides/islide/remove/#) | Elimina la diapositiva de la presentación. |
| [`reset(self)`](/slides/python-net/es/aspose.slides/islide/reset/#) | Restablece la posición, el tamaño y el formato de cada forma que tiene un prototipo en LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/islide/create_theme_effective/#) |  |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)