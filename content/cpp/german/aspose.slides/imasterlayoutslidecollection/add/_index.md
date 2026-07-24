---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Sammlung eine neue Layout-Folie am Ende hinzu.
type: docs
weight: 27
url: /de/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) Methode

Fügt der Sammlung eine neue Layout-Folie am Ende hinzu.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst. Wird ein null-Parameter übergeben, wird der Name automatisch in Abhängigkeit vom übergebenen Layout-Typ generiert (z. B. „Title Slide“ oder „1_Title Slide“, „2_..“ usw.). |

### Rückgabewert

Hinzugefügte Folie.

## Anmerkungen

1) Hinzugefügtes Layout für den Wert [SlideLayoutType::Custom](../../slidelayouttype/) von *layoutType* enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/), die über die Eigenschaft [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) aufgerufen wird.

## Siehe auch

* Aufzählung [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [String](../../../system/string/)
* Klasse [IMasterLayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)