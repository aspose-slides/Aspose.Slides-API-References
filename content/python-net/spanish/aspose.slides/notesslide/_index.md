---
title: NotesSlide class
second_title: Referencia de API de Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides/notesslide/
---
## NotesSlide clase

Representa una diapositiva de notas en una presentación.

**Herencia:**[`NotesSlide`](/slides/python-net/es/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)

El tipo NotesSlide expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shapes`](/slides/python-net/es/aspose.slides/notesslide/shapes/) | Devuelve las formas de una diapositiva.<br/>            Solo lectura [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/es/aspose.slides/notesslide/controls/) | Devuelve la colección de controles ActiveX en una diapositiva.<br/>            Solo lectura [`IControlCollection`](/slides/python-net/es/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/es/aspose.slides/notesslide/name/) | Devuelve o establece el nombre de una diapositiva.<br/>            Lectura/escritura **str**. |
| [`slide_id`](/slides/python-net/es/aspose.slides/notesslide/slide_id/) | Devuelve el ID de una diapositiva.<br/>            Solo lectura **int**. |
| [`custom_data`](/slides/python-net/es/aspose.slides/notesslide/custom_data/) | Devuelve los datos personalizados de la diapositiva.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/es/aspose.slides/notesslide/timeline/) | Devuelve el objeto de línea de tiempo de animación.<br/>            Solo lectura [`IAnimationTimeLine`](/slides/python-net/es/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/notesslide/slide_show_transition/) | Devuelve el objeto Transition que contiene información sobre<br/>            cómo avanza la diapositiva especificada durante una presentación.<br/>            Solo lectura [`ISlideShowTransition`](/slides/python-net/es/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/es/aspose.slides/notesslide/background/) | Devuelve el fondo de la diapositiva.<br/>            Solo lectura [`IBackground`](/slides/python-net/es/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/notesslide/hyperlink_queries/) | Proporciona acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/notesslide/show_master_shapes/) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no.<br/>            Lectura/escritura **bool**. |
| [`presentation`](/slides/python-net/es/aspose.slides/notesslide/presentation/) | Devuelve la interfaz IPresentation.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/notesslide/header_footer_manager/) | Devuelve el gestor HeaderFooter de la diapositiva de notas.<br/>            Solo lectura [`INotesSlideHeaderFooterManager`](/slides/python-net/es/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/es/aspose.slides/notesslide/notes_text_frame/) | Devuelve un TextFrame con el texto de notas si existe.<br/>            Solo lectura [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/es/aspose.slides/notesslide/theme_manager/) | Devuelve el gestor de tema sobrescrito.<br/>            Solo lectura [`IOverrideThemeManager`](/slides/python-net/es/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/es/aspose.slides/notesslide/parent_slide/) | Devuelve la diapositiva padre.<br/>            Solo lectura [`ISlide`](/slides/python-net/es/aspose.slides/islide). |
| [`slide`](/slides/python-net/es/aspose.slides/notesslide/slide/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/es/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/notesslide/equals/#ibaseslide) | Determina si las dos instancias IBaseSlide son iguales.<br/>            El valor devuelto se calcula en función de la estructura de la diapositiva y el contenido estático.<br/>            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y demás configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo SlideId, ni el contenido dinámico, por ejemplo el valor de fecha actual en Marcador de posición de Fecha. |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/notesslide/create_theme_effective/#) | Devuelve un tema efectivo para esta diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Encuentra la primera aparición de una forma con el texto alternativo especificado. |

### Ver también
* clase [`BaseSlide`](/slides/python-net/es/aspose.slides/baseslide)
* clase [`NotesSlide`](/slides/python-net/es/aspose.slides/notesslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)