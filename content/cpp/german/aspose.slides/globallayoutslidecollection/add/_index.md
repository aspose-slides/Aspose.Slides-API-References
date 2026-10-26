---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Präsentation eine neue Layout-Folie hinzu.
type: docs
weight: 14
url: /de/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) Methode

Fügt der Präsentation eine neue Layout-Folie hinzu.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-Folie für ein neues Layout. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst. Wenn ein null-Parameter übergeben wird, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ erzeugt (z. B. "Title Slide" oder "1_Title Slide", "2_..", usw.). |

### Rückgabewert

Hinzugefügte Folie.

## Bemerkungen

1) Das hinzugefügte Layout für den Wert [SlideLayoutType::Custom](../../slidelayouttype/) von *layoutType* enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/), auf die über die Eigenschaft [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) zugegriffen wird.

## Siehe auch

* Aufzählung [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Klasse [String](../../../system/string/)
* Klasse [GlobalLayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)