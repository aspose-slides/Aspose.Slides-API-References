---
title: add method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Agrega una nueva diapositiva de diseño al final de la colección.

### Devuelve

Diapositiva agregada.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/es/aspose.slides/slidelayouttype) | Tipo de diseño para un nuevo diseño.<br/><br/>            Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nombre para un nuevo diseño. Si el nombre pasado ya está en uso se lanzará ArgumentException.<br/><br/>            Si se pasa el parámetro None entonces el nombre se genera automáticamente en función del tipo de diseño pasado <br/><br/>            (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

### Observaciones

1) El diseño agregado para el valor SlideLayoutType.Custom de `layout_type` no contiene marcadores de posición ni formas.  
2) El análogo de este método es el método **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** accedido mediante la propiedad [`IPresentation.layout_slides`](/slides/python-net/es/aspose.slides/ipresentation/layout_slides).

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Se lanza si se pasa un valor no compatible del parámetro `layout_type`. Los tipos de diseño que no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si el valor del nombre de diseño `layout_name` ya está en uso en esta colección de diseños. |



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/imasterlayoutslidecollection)
* enumeración [`SlideLayoutType`](/slides/python-net/es/aspose.slides/slidelayouttype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)