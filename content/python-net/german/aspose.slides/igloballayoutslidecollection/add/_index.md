---
title: add method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Fügt der Präsentation eine neue Layout-Folie hinzu.

### Rückgabewert

Hinzugefügte Folie.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide) | Master-Folie für ein neues Layout. |
| layout_type | [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype) | Layout-Typ für ein neues Layout.<br/><br/>            Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst.<br/><br/>            Wenn der Parameter None übergeben wird, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert <br/><br/>            (zum Beispiel "Title Slide" oder "1_Title Slide", "2_..", etc.). |

### Anmerkungen

1) Hinzugefügtes Layout für den Wert SlideLayoutType.Custom von `layout_type` enthält keine Platzhalter und keine Formen.
2) Das Gegenstück dieser Methode ist die Methode **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** zugegriffen über die [`IMasterSlide.layout_slides`](/slides/python-net/de/aspose.slides/imasterslide/layout_slides)-Eigenschaft.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Ausgelöst, wenn ein nicht unterstützter Wert des Parameters `layout_type` übergeben wird. Layout-Typen, die derzeit nicht unterstützt werden: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ausgelöst, wenn `master` None ist. |
| **RuntimeError(Proxy error(ArgumentException))** | Ausgelöst, wenn `master` zu einer anderen Präsentation gehört. |
| **RuntimeError(Proxy error(ArgumentException))** | Ausgelöst, wenn der Layout-Name `layout_name` bereits in der Sammlung der Layouts von `master` verwendet wird. |



### Siehe auch
* Klasse [`IGlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/igloballayoutslidecollection)
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide)
* Aufzählung [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)