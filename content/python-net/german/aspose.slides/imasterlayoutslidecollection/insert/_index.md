---
title: insert method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Fügt eine neue Layout-Folie an der angegebenen Position der Sammlung ein.

### Rückgabewert

Eingefügte Folie.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| layout_type | [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype) | Layouttyp für ein neues Layout.<br/><br/>            Unterstützte Layouttypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andere Layouttypen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst.<br/><br/>            Wenn der Parameter None übergeben wird, wird der Name automatisch in Bezug auf den übergebenen Layouttyp erzeugt <br/><br/>            (z.B. "Title Slide" oder "1_Title Slide", "2_..", etc.). |

### Anmerkungen

Eingefügtes Layout für den Wert SlideLayoutType.Custom von `layout_type` 
            enthält keine Platzhalter und keine Formen.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Wird ausgelöst, wenn ein nicht unterstützter Wert des Parameters `layout_type` übergeben wird. Layouttypen, die derzeit nicht unterstützt werden: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn der Layoutname `layout_name` bereits in <br/>            dieser Sammlung von Layouts verwendet wird. |

### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/imasterlayoutslidecollection)
* Aufzählung [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)