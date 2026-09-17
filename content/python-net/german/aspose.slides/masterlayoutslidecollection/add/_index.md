---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Fügt der Sammlung am Ende eine neue Layout-Folie hinzu.

### Rückgabe

Hinzugefügte Folie.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype) | Layout-Typ für ein neues Layout.<br/><br/>            Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst.<br/><br/>            Wird ein None-Parameter übergeben, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert<br/><br/>            (zum Beispiel „Title Slide“ oder „1_Title Slide“, „2_…“ usw.). |

### Bemerkungen

1) Das hinzugefügte Layout für den Wert SlideLayoutType.Custom von `layout_type` enthält keine Platzhalter und keine Formen.
2) Das Gegenstück zu dieser Methode ist die Methode **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** über die Eigenschaft [`IPresentation.layout_slides`](/slides/python-net/de/aspose.slides/ipresentation/layout_slides) zugegriffen.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Wird ausgelöst, wenn ein nicht unterstützter Wert für den Parameter `layout_type` übergeben wird. Layout-Typen, die derzeit nicht unterstützt werden: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn der Layout-Name `layout_name` bereits in dieser Layout-Sammlung verwendet wird.<br/>            |

### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`MasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection)
* Aufzählung [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)