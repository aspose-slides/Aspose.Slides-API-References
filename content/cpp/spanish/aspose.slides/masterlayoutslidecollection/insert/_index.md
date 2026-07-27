---
title: Insert()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una nueva diapositiva de diseño en la posición especificada de la colección.
type: docs
weight: 40
url: /es/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) método

Inserta una nueva diapositiva de diseño en la posición especificada de la colección.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en relación con el tipo de diseño proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

### Valor devuelto

Diapositiva insertada.

## Observaciones

El diseño insertado para el valor [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* no contiene marcadores de posición ni formas. 

## Ver también

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)