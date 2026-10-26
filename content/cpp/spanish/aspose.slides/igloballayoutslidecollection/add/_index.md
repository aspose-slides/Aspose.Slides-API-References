---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva diapositiva de diseño a la presentación.
type: docs
weight: 14
url: /es/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) método


Agrega una nueva diapositiva de diseño a la presentación.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva maestra para un nuevo diseño. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, entonces el nombre se generará automáticamente en función del tipo de diseño pasado (por ejemplo \"Title Slide\" o \"1_Title Slide\", \"2_..\", etc.). |

### Valor devuelto

Diapositiva añadida.
## Observaciones



1) Se añadió un diseño para el valor [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* que no contiene marcadores de posición ni formas. 2) El análogo de este método es el método [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) al que se accede mediante la propiedad [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Ver también

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [IGlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)