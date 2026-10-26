---
title: Add()
second_title: Aspose.Slides per C++ Riferimento API
description: Aggiunge una nuova diapositiva di layout alla presentazione.
type: docs
weight: 14
url: /it/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method


Aggiunge una nuova diapositiva layout alla presentazione.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva master per un nuovo layout. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono supportati al momento: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata un'ArgumentException. Se viene passato un parametro null, il nome viene generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.). |

### Valore di ritorno

Diapositiva aggiunta.

## Osservazioni

1) Layout aggiunto per il valore [SlideLayoutType::Custom](../../slidelayouttype/) di *layoutType* non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) accessibile tramite la proprietà [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Vedi anche

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Classe [String](../../../system/string/)
* Classe [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)