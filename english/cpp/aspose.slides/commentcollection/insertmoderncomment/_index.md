---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API Reference
description: Insert new modern comment to a collection at the specified index.
type: docs
weight: 92
url: /cpp/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(**int32_t**, [System::String](../../../system/string/), [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>, [System::Drawing::PointF](../../../system.drawing/pointf/), [System::DateTime](../../../system/datetime/)) method


Insert new modern comment to a collection at the specified index.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of the element in a collection at which modern comment should be inserted. |
| text | [System::String](../../../system/string/) | Plain text of a new modern comment. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in a presentation where to add a new modern comment. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) on a slide to which a new modern comment is associated. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position on a slide where to add a new modern comment. |
| creationTime | [System::DateTime](../../../system/datetime/) | Time of a modern comment creation. |

### Return Value

Inserted modern comment.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IModernComment](../../imoderncomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [IShape](../../ishape/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
