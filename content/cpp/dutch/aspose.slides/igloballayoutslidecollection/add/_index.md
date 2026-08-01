---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe layoutdia toe aan de presentatie.
type: docs
weight: 14
url: /nl/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) methode


Voegt een nieuwe layoutdia toe aan de presentatie.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterdia voor een nieuwe layout. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layouttype voor een nieuwe layout. Ondersteunde layouttypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere layouttypes worden momenteel niet ondersteund: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Naam voor een nieuwe layout. Als de opgegeven naam al in gebruik is, wordt een ArgumentException opgegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven layouttype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", enz.). |

### Retourwaarde

Toegevoegde dia.
## Opmerkingen



1) Toegevoegde layout voor waarde [SlideLayoutType::Custom](../../slidelayouttype/) van *layoutType* bevat geen placeholders en geen vormen. 2) Een equivalent van deze methode is methode [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) die toegankelijk is via de [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/)-eigenschap. 

## Zie ook

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Klasse [String](../../../system/string/)
* Klasse [IGlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)