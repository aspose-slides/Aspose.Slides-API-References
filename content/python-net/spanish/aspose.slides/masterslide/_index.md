---
title: MasterSlide class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/masterslide/
---
## Clase MasterSlide

Representa una diapositiva maestra en una presentación.

**Herencia:**[`MasterSlide`](/slides/python-net/es/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)

El tipo MasterSlide expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shapes`](/slides/python-net/es/aspose.slides/masterslide/shapes/) | Devuelve las formas de una diapositiva.<br/>            Solo lectura [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/es/aspose.slides/masterslide/controls/) | Devuelve la colección de controles ActiveX en una diapositiva.<br/>            Solo lectura [`IControlCollection`](/slides/python-net/es/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/es/aspose.slides/masterslide/name/) | Devuelve o establece el nombre de una diapositiva maestra.<br/>            Lectura/escritura **str**. |
| [`slide_id`](/slides/python-net/es/aspose.slides/masterslide/slide_id/) | Devuelve el ID de una diapositiva.<br/>            Solo lectura **int**. |
| [`custom_data`](/slides/python-net/es/aspose.slides/masterslide/custom_data/) | Devuelve los datos personalizados de la diapositiva.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/es/aspose.slides/masterslide/timeline/) | Devuelve el objeto de línea de tiempo de animación.<br/>            Solo lectura [`IAnimationTimeLine`](/slides/python-net/es/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/masterslide/slide_show_transition/) | Devuelve el objeto Transition que contiene información sobre<br/>            cómo avanza la diapositiva especificada durante una presentación.<br/>            Solo lectura [`ISlideShowTransition`](/slides/python-net/es/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/es/aspose.slides/masterslide/background/) | Devuelve el fondo de la diapositiva.<br/>            Solo lectura [`IBackground`](/slides/python-net/es/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/masterslide/hyperlink_queries/) | Proporciona acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/masterslide/show_master_shapes/) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no.<br/>            Para la propia diapositiva maestra esta propiedad siempre devuelve `false`.<br/>            Lectura/escritura **bool**. |
| [`presentation`](/slides/python-net/es/aspose.slides/masterslide/presentation/) | Devuelve la interfaz IPresentation.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/masterslide/header_footer_manager/) | Devuelve el gestor HeaderFooter de la diapositiva maestra.<br/>            Solo lectura [`IMasterSlideHeaderFooterManager`](/slides/python-net/es/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/es/aspose.slides/masterslide/title_style/) | Devuelve el estilo de un texto de título.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/es/aspose.slides/masterslide/body_style/) | Devuelve el estilo de un texto de cuerpo.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/es/aspose.slides/masterslide/other_style/) | Devuelve el estilo de otro texto.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/es/aspose.slides/masterslide/layout_slides/) | Devuelve la colección de diapositivas de diseño hijo para esta diapositiva maestra.<br/>            Solo lectura [`IMasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/es/aspose.slides/masterslide/preserve/) | Determina si el maestro correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a ese maestro.<br/>            Nota: Aspose.Slides nunca eliminará ningún maestro no utilizado por sí mismo, para eliminar realmente los maestros no utilizados llame a **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Lectura/escritura **bool**. |
| [`has_depending_slides`](/slides/python-net/es/aspose.slides/masterslide/has_depending_slides/) | Devuelve true si existe al menos una diapositiva que depende de esta diapositiva maestra.<br/>            Solo lectura **bool**. |
| [`theme_manager`](/slides/python-net/es/aspose.slides/masterslide/theme_manager/) | Devuelve el gestor de temas.<br/>            Solo lectura [`IMasterThemeManager`](/slides/python-net/es/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/es/aspose.slides/masterslide/drawing_guides/) | Devuelve una colección de guías de dibujo para la diapositiva maestra.<br/>            Solo lectura [`IDrawingGuidesCollection`](/slides/python-net/es/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/es/aspose.slides/masterslide/slide/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/es/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/masterslide/equals/#ibaseslide) | Determina si las dos instancias de IBaseSlide son iguales.<br/>            El valor devuelto se calcula en base a la estructura de la diapositiva y al contenido estático.<br/>            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales.<br/>            La comparación no tiene en cuenta los valores de identificadores únicos, p. ej., SlideId y el contenido dinámico, p. ej., el valor de la fecha actual en el marcador de posición de fecha. |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/masterslide/create_theme_effective/#) | Devuelve un tema efectivo para esta diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Busca la primera aparición de una forma con el texto alternativo especificado. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/es/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Crea una nueva diapositiva maestra basada en la actual, aplicándole un tema externo <br/>            y aplica la diapositiva maestra creada a todas las diapositivas dependientes. |
| [`get_depending_slides(self)`](/slides/python-net/es/aspose.slides/masterslide/get_depending_slides/#) | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra. |

### Ver también
* clase [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)
* clase [`MasterSlide`](/slides/python-net/es/aspose.slides/masterslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)