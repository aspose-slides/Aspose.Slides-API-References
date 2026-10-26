---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe lay-out slide toe aan de presentatie.
type: docs
weight: 14
url: /nl/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) methode

Voegt een nieuwe lay-out-slide toe aan de presentatie.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-slide voor een nieuwe lay-out. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypen worden momenteel niet ondersteund: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt er een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", etc.). |

### Retourwaarde

Toegevoegde slide.

## Opmerkingen

1) Toegevoegde lay-out voor waarde [SlideLayoutType::Custom](../../slidelayouttype/) van *layoutType* bevat geen placeholders en geen vormen. 2) Het equivalent van deze methode is methode [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) die wordt benaderd via de eigenschap [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Zie ook

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Klasse [String](../../../system/string/)
* Klasse [GlobalLayoutSlideCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)