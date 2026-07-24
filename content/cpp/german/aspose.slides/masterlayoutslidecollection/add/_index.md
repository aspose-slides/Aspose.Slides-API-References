---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt der Sammlung am Ende eine neue Layout-Folie hinzu.
type: docs
weight: 27
url: /de/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) Methode


Fügt der Sammlung am Ende eine neue Layout-Folie hinzu.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layouttyp für ein neues Layout. Unterstützte Layouttypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layouttypen werden derzeit nicht unterstützt: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst. Wenn ein null-Parameter übergeben wird, wird der Name automatisch in Bezug auf den übergebenen Layouttyp generiert (z. B. "Title Slide" oder "1_Title Slide", "2_..", usw.). |

### Rückgabewert

Hinzugefügte Folie.

## Bemerkungen

1) Das hinzugefügte Layout für den Wert [SlideLayoutType::Custom](../../slidelayouttype/) von *layoutType* enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/), auf die über die Eigenschaft [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) zugegriffen wird. 

## Siehe auch

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [String](../../../system/string/)
* Klasse [MasterLayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)