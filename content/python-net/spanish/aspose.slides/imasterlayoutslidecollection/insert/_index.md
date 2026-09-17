---
title: insert method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Inserta una nueva diapositiva de diseño en la posición especificada de la colección.

### Devuelve

Diapositiva insertada.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice de la nueva diapositiva. |
| layout_type | [`SlideLayoutType`](/slides/python-net/es/aspose.slides/slidelayouttype) | Tipo de diseño para un nuevo diseño.<br/><br/>            Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Otros tipos de diseño no son compatibles actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException.<br/><br/>            Si se pasa el parámetro None, entonces el nombre se genera automáticamente en función del tipo de diseño proporcionado <br/><br/>            (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

### Observaciones

El diseño insertado para el valor SlideLayoutType.Custom de `layout_type` no contiene marcadores de posición ni formas.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Se lanza si se pasa un valor no compatible del parámetro `layout_type`. Tipos de diseño que no son compatibles actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si el valor del nombre de diseño `layout_name` ya está en uso en esta colección de diseños. |



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/imasterlayoutslidecollection)
* enumeración [`SlideLayoutType`](/slides/python-net/es/aspose.slides/slidelayouttype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)