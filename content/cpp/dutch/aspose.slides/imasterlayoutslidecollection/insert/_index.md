---
title: Insert()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe lay-outdia toe op de opgegeven positie van de collectie.
type: docs
weight: 40
url: /nl/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) methode


Voegt een nieuwe lay-outdia toe op de opgegeven positie van de collectie.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van de nieuwe dia. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypes worden momenteel niet ondersteund: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt opgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", etc.). |

### Retourwaarde

Ingevoegde dia.

## Opmerkingen

Ingevoegde lay-out voor waarde [SlideLayoutType::Custom](../../slidelayouttype/) van *layoutType* bevat geen plaatsaanduidingen en geen vormen. 

## Zie ook

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)