---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/icommentcollection/insert_comment/
weight: 40
---


## insert_comment {#int-str-asposeslidesislide-asposepydrawingpointf-systemdatetime}
Insert new comment to a collection at the specified index.

### Returns

Inserted comment.



```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index of the element in a collection at which comment should be inserted. |
| text | **str** | Plain text of a new comment. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Slide in a presentation where to add a new comment. |
| position | **aspose.pydrawing.PointF** | Position on a slide where to add a new comment. |
| creation_time | **System.DateTime** | Time of a comment creation. |



### See Also
* class [`ICommentCollection`](/slides/python-net/aspose.slides/icommentcollection)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

