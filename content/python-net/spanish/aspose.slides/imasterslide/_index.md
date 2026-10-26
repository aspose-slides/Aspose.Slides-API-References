---
title: IMasterSlide class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/imasterslide/
---
## IMasterSlide clase

Representa una diapositiva maestra en una presentación.

El tipo IMasterSlide expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/imasterslide/header_footer_manager/) | Devuelve el administrador HeaderFooter de la diapositiva maestra.<br/>            Solo lectura [`IMasterSlideHeaderFooterManager`](/slides/python-net/es/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/es/aspose.slides/imasterslide/title_style/) | Devuelve el estilo de un texto de título.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/es/aspose.slides/imasterslide/body_style/) | Devuelve el estilo de un texto del cuerpo.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/es/aspose.slides/imasterslide/other_style/) | Devuelve el estilo de otro texto.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/es/aspose.slides/imasterslide/layout_slides/) | Devuelve la colección de diapositivas de diseño secundarias para esta diapositiva maestra.<br/>            Solo lectura [`IMasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/es/aspose.slides/imasterslide/preserve/) | Determina si la maestra correspondiente se elimina cuando todas <br/>            las diapositivas que siguen a esa maestra se eliminan.<br/>            Nota: Aspose.Slides nunca eliminará ninguna maestra sin usar por sí misma, <br/>            para eliminar realmente maestras sin usar llame a **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Lectura/escritura **bool**. |
| [`has_depending_slides`](/slides/python-net/es/aspose.slides/imasterslide/has_depending_slides/) | Devuelve true si existe al menos una diapositiva que depende de esta diapositiva maestra.<br/>            Solo lectura **bool**. |
| [`drawing_guides`](/slides/python-net/es/aspose.slides/imasterslide/drawing_guides/) | Devuelve una colección de guías de dibujo para la diapositiva maestra.<br/>            Solo lectura [`IDrawingGuidesCollection`](/slides/python-net/es/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/es/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/es/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/es/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/es/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/es/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/es/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/es/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/es/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/es/aspose.slides/imasterslide/theme_manager/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/es/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Crea una nueva diapositiva maestra basada en la actual, aplicando un tema externo a ella <br/>            y aplica la diapositiva maestra creada a todas las diapositivas dependientes. |
| [`get_depending_slides(self)`](/slides/python-net/es/aspose.slides/imasterslide/get_depending_slides/#) | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)