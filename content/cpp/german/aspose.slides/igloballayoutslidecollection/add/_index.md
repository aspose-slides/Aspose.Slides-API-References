---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Präsentation eine neue Layout-Folie hinzu.
type: docs
weight: 14
url: /de/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) Methode

Fügt der Präsentation eine neue Layout-Folie hinzu.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-Folie für ein neues Layout. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Name für ein neues Layout. Wird ein bereits verwendeter Name übergeben, wird eine ArgumentException ausgelöst. Wird ein null-Parameter übergeben, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert (zum Beispiel "Title Slide" oder "1_Title Slide", "2_..", usw.). |

### Rückgabewert

Hinzugefügte Folie.

## Anmerkungen

1) Das hinzugefügte Layout für den Wert [SlideLayoutType::Custom](../../slidelayouttype/) von *layoutType* enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/), auf die über die Eigenschaft [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) zugegriffen wird.

## Siehe auch

* Aufzählung [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Klasse [String](../../../system/string/)
* Klasse [IGlobalLayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)