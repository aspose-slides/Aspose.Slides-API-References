---
title: Insert()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt eine neue Layout-Folie an der angegebenen Position der Sammlung ein.
type: docs
weight: 40
url: /de/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) Methode

Fügt eine neue Layout-Folie an der angegebenen Position der Sammlung ein.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index der neuen Folie. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst. Wenn ein null-Parameter übergeben wird, wird der Name automatisch in Abhängigkeit vom übergebenen Layout-Typ generiert (z. B. \"Title Slide\" oder \"1_Title Slide\", \"2_..\", usw.). |

### Rückgabewert

Eingefügte Folie.

## Anmerkungen

Eingefügtes Layout für den Wert [SlideLayoutType::Custom](../../slidelayouttype/) von *layoutType* enthält keine Platzhalter und keine Formen. 

## Siehe auch

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [String](../../../system/string/)
* Klasse [MasterLayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)