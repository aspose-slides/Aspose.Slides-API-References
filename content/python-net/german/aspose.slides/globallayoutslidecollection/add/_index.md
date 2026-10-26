---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/globallayoutslidecollection/add/
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
| layout_type | [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype) | Layout-Typ für ein neues Layout.<br/><br/>            Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Weitere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name für ein neues Layout. Wird ein bereits verwendeter Name übergeben, wird eine ArgumentException ausgelöst.<br/><br/>            Wird der Parameter None übergeben, wird der Name automatisch in Abhängigkeit vom übergebenen Layout-Typ erzeugt.<br/><br/>            (zum Beispiel "Title Slide" oder "1_Title Slide", "2_..", etc.). |

### Anmerkungen

1) Hinzugefügtes Layout für den Wert SlideLayoutType.Custom von `layout_type` enthält keine Platzhalter und keine Formen.  
2) Das Gegenstück zu dieser Methode ist die Methode **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**,
auf die über die Eigenschaft [`IMasterSlide.layout_slides`](/slides/python-net/de/aspose.slides/imasterslide/layout_slides) zugegriffen wird.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Wird ein nicht unterstützter Wert für den Parameter `layout_type` übergeben, wird diese Ausnahme ausgelöst. Layout-Typen, die derzeit nicht unterstützt werden: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wird `master` None übergeben, wird diese Ausnahme ausgelöst. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird `master` zu einer anderen Präsentation gehören, wird diese Ausnahme ausgelöst. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird der Layout-Namenswert `layout_name` bereits in der Sammlung der Layouts von `master` verwendet, wird diese Ausnahme ausgelöst. |



### Siehe auch
* Klasse [`GlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/globallayoutslidecollection)
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide)
* Enumeration [`SlideLayoutType`](/slides/python-net/de/aspose.slides/slidelayouttype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)