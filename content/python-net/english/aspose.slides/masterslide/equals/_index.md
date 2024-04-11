---
title: equals method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/masterslide/equals/
weight: 30
---


## equals {#IBaseSlide}
Determines whether the two IBaseSlide instances are equal.
            Returning value is calculated based on slide's structure and static content.
            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder.

### Returns

**true**  if the specified IBaseSlide is equal to the current IBaseSlide; 
            otherwise, **false** .



```python
def equals(self, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| slide | IBaseSlide | The IBaseSlide to compare with the current IBaseSlide. |



