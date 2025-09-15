---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---


## get_text_boxes_contains_text {#ibaseslide-str-bool}
Returns all text frames on the specified slide that contain the given text.

### Returns

An array of [`ITextFrame`](/slides/python-net/aspose.slides/itextframe) objects that contain the specified text.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide) | The slide to search. |
| text | **str** | The text to search for within text frames. |
| check_placeholder_text | **bool** | Indicates whether to include text frames that are empty, but whose placeholder text contains the search text. |



### See Also
* class [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide)
* class [`ITextFrame`](/slides/python-net/aspose.slides/itextframe)
* class [`SlideUtil`](/slides/python-net/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)

