---
title: MasterNotesSlide class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/masternotesslide/
---
## MasterNotesSlide clase

Representa la diapositiva maestra para notas.

**Herencia:**[`MasterNotesSlide`](/slides/python-net/es/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)

El tipo MasterNotesSlide expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shapes`](/slides/python-net/es/aspose.slides/masternotesslide/shapes/) | Devuelve las formas de una diapositiva.<br/>            Solo lectura [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/es/aspose.slides/masternotesslide/controls/) | Devuelve la colección de controles ActiveX en una diapositiva.<br/>            Solo lectura [`IControlCollection`](/slides/python-net/es/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/es/aspose.slides/masternotesslide/name/) | Devuelve o establece el nombre de una diapositiva.<br/>            Lectura/escritura **str**. |
| [`slide_id`](/slides/python-net/es/aspose.slides/masternotesslide/slide_id/) | Devuelve el ID de una diapositiva.<br/>            Solo lectura **int**. |
| [`custom_data`](/slides/python-net/es/aspose.slides/masternotesslide/custom_data/) | Devuelve los datos personalizados de la diapositiva.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/es/aspose.slides/masternotesslide/timeline/) | Devuelve el objeto de línea de tiempo de animación.<br/>            Solo lectura [`IAnimationTimeLine`](/slides/python-net/es/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/masternotesslide/slide_show_transition/) | Devuelve el objeto Transition que contiene información sobre<br/>            cómo avanza la diapositiva especificada durante una presentación.<br/>            Solo lectura [`ISlideShowTransition`](/slides/python-net/es/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/es/aspose.slides/masternotesslide/background/) | Devuelve el fondo de la diapositiva.<br/>            Solo lectura [`IBackground`](/slides/python-net/es/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/masternotesslide/hyperlink_queries/) | Proporciona acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/masternotesslide/show_master_shapes/) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no.<br/>            Para la propia diapositiva maestra esta propiedad siempre devuelve `false`.<br/>            Lectura/escritura **bool**. |
| [`presentation`](/slides/python-net/es/aspose.slides/masternotesslide/presentation/) | Devuelve la interfaz IPresentation.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/masternotesslide/header_footer_manager/) | Devuelve el gestor HeaderFooter de la diapositiva maestra de notas.<br/>            Solo lectura [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/es/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/es/aspose.slides/masternotesslide/theme_manager/) | Devuelve el gestor de temas.<br/>            Solo lectura [`IMasterThemeManager`](/slides/python-net/es/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/es/aspose.slides/masternotesslide/notes_style/) | Devuelve el estilo de un texto de notas.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/es/aspose.slides/masternotesslide/drawing_guides/) | Devuelve una colección de guías de dibujo para la diapositiva maestra de notas.<br/>            Solo lectura [`IDrawingGuidesCollection`](/slides/python-net/es/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/es/aspose.slides/masternotesslide/slide/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/es/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/masternotesslide/equals/#ibaseslide) | Determina si las dos instancias IBaseSlide son iguales.<br/>            El valor devuelto se calcula basado en la estructura de la diapositiva y el contenido estático.<br/>            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej., SlideId, ni el contenido dinámico, p. ej., el valor de fecha actual en el marcador de posición Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/masternotesslide/create_theme_effective/#) | Devuelve un tema efectivo para esta diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Busca la primera ocurrencia de una forma con el texto alternativo especificado. |


### Ver también
* clase [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)
* clase [`MasterNotesSlide`](/slides/python-net/es/aspose.slides/masternotesslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)