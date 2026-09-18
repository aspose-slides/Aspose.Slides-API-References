---
title: insert method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Beszúr egy új elrendezési diát a gyűjtemény megadott pozíciójába.

### Visszatér

A beszúrt dia.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az új dia indexe. |
| layout_type | [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype) | Layout type for a new layout.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name for a new layout. If passed name is already in use the ArgumentException will be thrown.<br/><br/>            If None parameter is passed then name genarated atomatically in regards to passed layout type <br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### Megjegyzés

Inserted layout for value SlideLayoutType.Custom of `layout_type` 
            contains no placeholders and no shapes.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Thrown if unsupported value of parameter `layout_type` is passed. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if layout name value `layout_name` is already in use in <br/>            this collection of the layouts. |



### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection)
* enumeráció [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)