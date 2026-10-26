---
title: Slide class
second_title: Referencia de la API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/slide/
---
## Clase Slide

Representa una diapositiva en una presentación.

**Herencia:**[`Slide`](/slides/python-net/es/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)

El tipo Slide expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shapes`](/slides/python-net/es/aspose.slides/slide/shapes/) | Devuelve las formas de una diapositiva.<br/>            Solo lectura [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/es/aspose.slides/slide/controls/) | Devuelve la colección de controles ActiveX en una diapositiva.<br/>            Solo lectura [`IControlCollection`](/slides/python-net/es/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/es/aspose.slides/slide/name/) | Devuelve o establece el nombre de una diapositiva.<br/>            Lectura/escritura **str**. |
| [`slide_id`](/slides/python-net/es/aspose.slides/slide/slide_id/) | Devuelve el ID de una diapositiva.<br/>            Solo lectura **int**. |
| [`custom_data`](/slides/python-net/es/aspose.slides/slide/custom_data/) | Devuelve los datos personalizados de la diapositiva.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/es/aspose.slides/slide/timeline/) | Devuelve el objeto de la línea de tiempo de animación.<br/>            Solo lectura [`IAnimationTimeLine`](/slides/python-net/es/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/slide/slide_show_transition/) | Devuelve el objeto Transition que contiene información sobre<br/>            cómo avanza la diapositiva especificada durante una presentación.<br/>            Solo lectura [`ISlideShowTransition`](/slides/python-net/es/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/es/aspose.slides/slide/background/) | Devuelve el fondo de la diapositiva.<br/>            Solo lectura [`IBackground`](/slides/python-net/es/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/slide/hyperlink_queries/) | Proporciona acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/slide/show_master_shapes/) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no.<br/>            Lectura/escritura **bool**. |
| [`presentation`](/slides/python-net/es/aspose.slides/slide/presentation/) | Devuelve la interfaz IPresentation.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/slide/header_footer_manager/) | Devuelve el administrador HeaderFooter de la diapositiva.<br/>            Solo lectura [`ISlideHeaderFooterManager`](/slides/python-net/es/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/es/aspose.slides/slide/theme_manager/) | Devuelve el administrador de tema de anulación.<br/>            Solo lectura [`IOverrideThemeManager`](/slides/python-net/es/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/es/aspose.slides/slide/slide_number/) | Devuelve el número de la diapositiva.<br/>            El índice de la diapositiva en la colección [`Presentation.slides`](/slides/python-net/es/aspose.slides/presentation/slides) siempre es igual a SlideNumber - Presentation.FirstSlideNumber.<br/>            Lectura/escritura **int**. |
| [`hidden`](/slides/python-net/es/aspose.slides/slide/hidden/) | Determina si la diapositiva especificada está oculta durante una presentación.<br/>            Lectura/escritura **bool**. |
| [`layout_slide`](/slides/python-net/es/aspose.slides/slide/layout_slide/) | Devuelve o establece la diapositiva de diseño para la diapositiva actual.<br/>            Lectura/escritura [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/es/aspose.slides/slide/notes_slide_manager/) | Permite acceder a la diapositiva de notas, agregarla y eliminarla.<br/>            Solo lectura [`INotesSlideManager`](/slides/python-net/es/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/es/aspose.slides/slide/slide/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/slide/join_portions_with_same_formatting/#) | Une fragmentos con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/es/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Une fragmentos con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/slide/get_image/#float-float) | Devuelve un objeto Thumbnail Image con escalado personalizado. |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/slide/get_image/#) | Devuelve un objeto Thumbnail Image (20% del tamaño real). |
| [`get_image(self, image_size)`](/slides/python-net/es/aspose.slides/slide/get_image/#asposeslidessize) | Devuelve un objeto Thumbnail Image con tamaño especificado. |
| [`get_image(self, options)`](/slides/python-net/es/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Devuelve un objeto de imagen tiff Thumbnail con parámetros especificados. |
| [`get_image(self, options)`](/slides/python-net/es/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Devuelve un objeto Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Devuelve un objeto Thumbnail Image con escalado personalizado. |
| [`get_image(self, options, image_size)`](/slides/python-net/es/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Devuelve un objeto Thumbnail Image con tamaño especificado. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/slide/write_as_svg/#iorawiobase) | Guarda el contenido de la diapositiva como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la diapositiva como archivo SVG. |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/slide/equals/#ibaseslide) | Determina si las dos instancias de IBaseSlide son iguales.<br/>            El valor devuelto se calcula en base a la estructura de la diapositiva y su contenido estático.<br/>            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo SlideId, y el contenido dinámico, por ejemplo el valor de fecha actual en el Marcador de posición de fecha. |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/slide/create_theme_effective/#) | Devuelve un tema efectivo para esta diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/slide/find_shape_by_alt_text/#str) | Encuentra la primera aparición de una forma con el texto alternativo especificado. |
| [`write_as_emf(self, stream)`](/slides/python-net/es/aspose.slides/slide/write_as_emf/#iorawiobase) | Guarda el contenido de la diapositiva como archivo EMF. |
| [`remove(self)`](/slides/python-net/es/aspose.slides/slide/remove/#) | Elimina la diapositiva de la presentación. |
| [`reset(self)`](/slides/python-net/es/aspose.slides/slide/reset/#) | Restablece la posición, tamaño y formato de cada forma que tiene un prototipo en LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/es/aspose.slides/slide/get_slide_comments/#icommentauthor) | Devuelve todos los comentarios de diapositiva añadidos por un autor específico. |

### Ver también
* clase [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)
* clase [`Slide`](/slides/python-net/es/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)