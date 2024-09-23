---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/masterlayoutslidecollection/add/
weight: 10
---


## add {#slidelayouttype-str}
Adds a new layout slide to the end of the collection.

### Returns

Added slide.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/aspose.slides/slidelayouttype) | Layout type for a new layout.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Name for a new layout. If passed name is already in use the ArgumentException will be thrown.<br/><br/>            If None parameter is passed then name genarated atomatically in regards to passed layout type <br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### Remarks

1) Added layout for value SlideLayoutType.Custom of `layout_type` 
            contains no placeholders and no shapes.
            2) Analogue of this method is 
            method **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**
            accessed with [`IPresentation.layout_slides`](/slides/python-net/aspose.slides/ipresentation/layout_slides) property.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Thrown if unsupported value of parameter `layout_type` is passed. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if layout name value `layout_name` is already in use in <br/>            this collection of the layouts. |



### See Also
* class [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide)
* class [`MasterLayoutSlideCollection`](/slides/python-net/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

