---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una nueva diapositiva de diseño al final de la colección.
type: docs
weight: 27
url: /es/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method


Agrega una nueva diapositiva de diseño al final de la colección.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo \"Title Slide\" o \"1_Title Slide\", \"2_..\", etc.). |

### Valor de retorno

Diapositiva agregada.
## Observaciones



1) El diseño agregado para el valor [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* no contiene marcadores de posición ni formas. 2) El análogo de este método es el método [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) al que se accede mediante la propiedad [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## Ver también

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)