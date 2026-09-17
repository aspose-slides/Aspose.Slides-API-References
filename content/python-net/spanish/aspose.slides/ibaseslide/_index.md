---
title: IBaseSlide class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ibaseslide/
---
## IBaseSlide clase

Representa datos comunes para todos los tipos de diapositiva.

El tipo IBaseSlide expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shapes`](/slides/python-net/es/aspose.slides/ibaseslide/shapes/) | Devuelve las formas de una diapositiva.<br/>            Solo lectura [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/es/aspose.slides/ibaseslide/controls/) | Devuelve la colección de controles ActiveX en una diapositiva.<br/>            Solo lectura [`IControlCollection`](/slides/python-net/es/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/es/aspose.slides/ibaseslide/name/) | Devuelve o establece el nombre de una diapositiva.<br/>            Lectura/escritura **str**. |
| [`slide_id`](/slides/python-net/es/aspose.slides/ibaseslide/slide_id/) | Devuelve el ID de una diapositiva.<br/>            Solo lectura **int**. |
| [`custom_data`](/slides/python-net/es/aspose.slides/ibaseslide/custom_data/) | Devuelve los datos personalizados de la diapositiva.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/es/aspose.slides/ibaseslide/timeline/) | Devuelve el objeto de línea de tiempo de animación.<br/>            Solo lectura [`IAnimationTimeLine`](/slides/python-net/es/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/es/aspose.slides/ibaseslide/slide_show_transition/) | Devuelve el objeto TransitionEx que contiene información sobre<br/>            cómo avanza la diapositiva especificada durante una presentación.<br/>            Solo lectura [`ISlideShowTransition`](/slides/python-net/es/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/es/aspose.slides/ibaseslide/background/) | Devuelve el fondo de la diapositiva.<br/>            Solo lectura [`IBackground`](/slides/python-net/es/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/ibaseslide/hyperlink_queries/) | Proporciona acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/es/aspose.slides/ibaseslide/show_master_shapes/) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no.<br/>            Para la propia diapositiva maestra, esta propiedad siempre devuelve `false`.<br/>            Lectura/escritura **bool**. |
| [`slide`](/slides/python-net/es/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/ibaseslide/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/es/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Encuentra la primera aparición de una forma con el texto alternativo especificado. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Une secuencias con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [`equals(self, slide)`](/slides/python-net/es/aspose.slides/ibaseslide/equals/#ibaseslide) | Determina si los dos objetos IBaseSlide son iguales.<br/>            El valor devuelto se calcula basándose en la estructura y el contenido estático de la diapositiva.<br/>            Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y demás configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo SlideId, ni el contenido dinámico, por ejemplo el valor de la fecha actual en el marcador de posición de fecha. |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)