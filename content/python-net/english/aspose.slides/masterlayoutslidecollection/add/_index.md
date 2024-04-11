---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/masterlayoutslidecollection/add/
weight: 70
---


## add {#SlideLayoutType-string}
Adds a new layout slide to the end of the collection.

### Returns

Added slide.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| layout_type | SlideLayoutType | Layout type for a new layout.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | string | Name for a new layout. If passed name is already in use the ArgumentException will be thrown.<br/><br/>            If null parameter is passed then name genarated atomatically in regards to passed layout type <br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### Remarks

1) Added layout for value SlideLayoutType.Custom of `
layout_type`
 
            contains no placeholders and no shapes.
            2) Analogue of this method is 
            method Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste.
            accessed with [`IPresentation.layout_slides`](/slides/python-net/aspose.slides/ipresentation#layout_slides) property.

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.NotImplementedException | Thrown if unsupported value of parameter `<br/>layout_type`<br/> is passed. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| .NET type System.ArgumentException | Thrown if layout name value `<br/>layout_name`<br/> is already in use in <br/>            this collection of the layouts. |



