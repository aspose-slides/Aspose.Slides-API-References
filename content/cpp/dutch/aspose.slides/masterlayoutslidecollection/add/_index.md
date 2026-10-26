---
title: Add()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt een nieuwe lay-outdia toe aan het einde van de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method

Voegt een nieuwe lay-outdia toe aan het einde van de collectie.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypen worden momenteel niet ondersteund: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", enz.). |

### Retourwaarde

Toegevoegde dia.

## Opmerkingen

1) Toegevoegde lay-out voor waarde [SlideLayoutType::Custom](../../slidelayouttype/) van *layoutType* bevat geen tijdelijke aanduidingen en geen vormen. 2) Het analoge van deze methode is methode [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) toegankelijk via eigenschap [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Zie ook

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [String](../../../system/string/)
* Klasse [MasterLayoutSlideCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)