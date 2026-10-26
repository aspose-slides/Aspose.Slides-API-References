---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una diapositiva de diseño nueva a la presentación.
type: docs
weight: 14
url: /es/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) método

Agrega una diapositiva de diseño nueva a la presentación.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva maestra para un nuevo diseño. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo de diseño para un nuevo diseño. Los tipos de diseño soportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se genera automáticamente en función del tipo de diseño proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

### Valor devuelto

Diapositiva añadida.

## Observaciones

1) El diseño añadido para el valor [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* no contiene marcadores de posición ni formas. 2) El análogo de este método es el método [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) al que se accede mediante la propiedad [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Ver también

* Enumeración [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [IMasterSlide](../../imasterslide/)
* Clase [String](../../../system/string/)
* Clase [GlobalLayoutSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)