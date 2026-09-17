---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Fügt am Ende der Sammlung eine neue Layout-Folie hinzu.

### Returns

Hinzugefügte Folie.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype) | Layout-Typ für ein neues Layout.<br/><br/>            Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Weitere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst.<br/><br/>            Wenn der Parameter None übergeben wird, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert <br/><br/>            (zum Beispiel "Title Slide" oder "1_Title Slide", "2_..", usw.). |

### Remarks

1) Hinzugefügtes Layout für den Wert SlideLayoutType.Custom von `layout_type` enthält keine Platzhalter und keine Formen.
2) Das Gegenstück zu dieser Methode ist die Methode **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** zugegriffen über die [`IPresentation.layout_slides`](/slides/python-net/de/aspose.slides/ipresentation/layout_slides)-Eigenschaft.

### Exceptions

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Wird ausgelöst, wenn ein nicht unterstützter Wert des Parameters `layout_type` übergeben wird. Layout-Typen, die derzeit nicht unterstützt werden: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn der Layout-Name `layout_name` bereits in dieser Sammlung von Layouts verwendet wird.<br/>            |

### See Also
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/imasterlayoutslidecollection)
* Aufzählung [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)