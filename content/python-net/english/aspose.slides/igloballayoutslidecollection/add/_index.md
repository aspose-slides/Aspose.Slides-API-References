---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igloballayoutslidecollection/add/
weight: 10
---


## add {#imasterslide-slidelayouttype-str}
Adds a new layout slide to the presentation.

### Returns

Added slide.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/aspose.slides/imasterslide) | Master slide for a new layout. |
| layout_type | [`SlideLayoutType`](/slides/python-net/aspose.slides/slidelayouttype) | Layout type for a new layout.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name for a new layout. If passed name is already in use the ArgumentException will be thrown.<br/><br/>            If null parameter is passed then name genarated atomatically in regards to passed layout type <br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### Remarks

1) Added layout for value SlideLayoutType.Custom of `
layout_type`
 
            contains no placeholders and no shapes.
            2) Analogue of this method is method **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**
            accessed with [`IMasterSlide.layout_slides`](/slides/python-net/aspose.slides/imasterslide/layout_slides) property.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Thrown if unsupported value of parameter `<br/>layout_type`<br/> is passed. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Thrown if `<br/>master`<br/> is null. |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if `<br/>master`<br/> belongs to the other presentation. |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if layout name value `<br/>layout_name`<br/> is already in use in <br/>            collection of the layouts of `<br/>master`<br/>. |



### See Also
* class [`IGlobalLayoutSlideCollection`](/slides/python-net/aspose.slides/igloballayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/aspose.slides/imasterslide)
* enumeration [`SlideLayoutType`](/slides/python-net/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

