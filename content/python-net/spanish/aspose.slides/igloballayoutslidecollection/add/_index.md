---
title: add method
second_title: Aspose.Slides para Python a través de la API de .NET
description: 
type: docs
url: /es/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Agrega una nueva diapositiva de diseño a la presentación.

### Devuelve

Diapositiva agregada.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño. |
| layout_type | [`SlideLayoutType`](/slides/python-net/es/aspose.slides/slidelayouttype) | Tipo de diseño para un nuevo diseño.<br/><br/>            Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso, se lanzará ArgumentException.<br/><br/>            Si se pasa el parámetro None, entonces el nombre se genera automáticamente en relación con el tipo de diseño proporcionado <br/><br/>            (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

### Observaciones

1) El diseño añadido para el valor SlideLayoutType.Custom de `layout_type` no contiene marcadores de posición ni formas.  
2) El análogo de este método es el método **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** accedido mediante la propiedad [`IMasterSlide.layout_slides`](/slides/python-net/es/aspose.slides/imasterslide/layout_slides).

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Lanzado si se pasa un valor no soportado del parámetro `layout_type`. Tipos de diseño que no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lanzado si `master` es None. |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzado si `master` pertenece a otra presentación. |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzado si el valor del nombre de diseño `layout_name` ya está en uso en la colección de diseños de `master`. |



### Ver también
* clase [`IGlobalLayoutSlideCollection`](/slides/python-net/es/aspose.slides/igloballayoutslidecollection)
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide)
* enumeración [`SlideLayoutType`](/slides/python-net/es/aspose.slides/slidelayouttype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)