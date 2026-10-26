---
title: LayoutSlide class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/layoutslide/
---
## LayoutSlide clase

Representa un LayoutSlide.

**Herencia:**[`LayoutSlide`](/slides/python-net/es/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)

El tipo LayoutSlide expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shapes`](/slides/python-net/es/aspose.slides/layoutslide/shapes/) | Devuelve las formas de una diapositiva.<br/>            Solo lectura [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/es/aspose.slides/layoutslide/controls/) | Devuelve la colección de controles ActiveX en una diapositiva.<br/>            Solo lectura [`IControlCollection`](/slides/python-net/es/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/es/aspose.slides/layoutslide/name/) | Devuelve o establece el nombre de una diapositiva.<br/>            Lectura/escritura **str**. |
| [`slide_id`](/slides/python-net/es/aspose.slides/layoutslide/slide_id/) | Devuelve el ID de una diapositiva.<br/>            Solo lectura **int**. |
| [`custom_data`](/slides/python-net/es/aspose.slides/layoutslide/custom_data/) | Devuelve los datos personalizados de la diapositiva.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/es/aspose.slides/layoutslide/timeline/) | Devuelve el objeto de línea de tiempo de animación.<br/>            Solo lectura [`IAnimationTimeLine`](/slides/python-net/es/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/layoutslide/slide_show_transition/) | Devuelve el objeto Transition que contiene información sobre<br/>            cómo avanza la diapositiva especificada durante una presentación.<br/>            Solo lectura [`ISlideShowTransition`](/slides/python-net/es/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/es/aspose.slides/layoutslide/background/) | Devuelve el fondo de la diapositiva.<br/>            Solo lectura [`IBackground`](/slides/python-net/es/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/layoutslide/hyperlink_queries/) | Proporciona un acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/layoutslide/show_master_shapes/) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no.<br/>            Lectura/escritura **bool**. |
| [`presentation`](/slides/python-net/es/aspose.slides/layoutslide/presentation/) | Devuelve la interfaz IPresentation.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/layoutslide/header_footer_manager/) | Devuelve el gestor HeaderFooter de la diapositiva de diseño.<br/>            Solo lectura [`ILayoutSlideHeaderFooterManager`](/slides/python-net/es/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/es/aspose.slides/layoutslide/placeholder_manager/) | Devuelve el gestor de marcadores de posición de la diapositiva de diseño.<br/>            Solo lectura [`ILayoutPlaceholderManager`](/slides/python-net/es/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/es/aspose.slides/layoutslide/master_slide/) | Devuelve o establece la diapositiva maestra para un diseño.<br/>            Lectura/escritura [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/es/aspose.slides/layoutslide/theme_manager/) | Devuelve el gestor de temas de anulación.<br/>            Solo lectura [`IOverrideThemeManager`](/slides/python-net/es/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/es/aspose.slides/layoutslide/layout_type/) | Devuelve el tipo de diseño de esta diapositiva de diseño.<br/>            Solo lectura [`SlideLayoutType`](/slides/python-net/es/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/es/aspose.slides/layoutslide/has_depending_slides/) | Devuelve verdadero si existe al menos una diapositiva que dependa de esta diapositiva de diseño.<br/>            Solo lectura **bool**. |
| [`drawing_guides`](/slides/python-net/es/aspose.slides/layoutslide/drawing_guides/) | Devuelve una colección de guías de dibujo para la diapositiva de diseño.<br/>            Solo lectura [`IDrawingGuidesCollection`](/slides/python-net/es/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/es/aspose.slides/layoutslide/slide/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Combina ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/es/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Combina ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/layoutslide/equals/#ibaseslide) | Determina si dos instancias de IBaseSlide son iguales.<br/>            El valor devuelto se calcula en base a la estructura de la diapositiva y al contenido estático.<br/>            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej. SlideId y el contenido dinámico, p. ej. el valor de la fecha actual en Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/layoutslide/create_theme_effective/#) | Devuelve un tema efectivo para esta diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Encuentra la primera aparición de una forma con el texto alternativo especificado. |
| [`remove(self)`](/slides/python-net/es/aspose.slides/layoutslide/remove/#) | Elimina el diseño de la presentación. |
| [`get_depending_slides(self)`](/slides/python-net/es/aspose.slides/layoutslide/get_depending_slides/#) | Devuelve una matriz con todas las diapositivas que dependen de este diseño de diapositiva. |


### Ver también
* clase [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)
* clase [`LayoutSlide`](/slides/python-net/es/aspose.slides/layoutslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)