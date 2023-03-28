---
title: InsertComment()
second_title: Aspose.Slides for C++ API Reference
description: Insert new comment to a collection at the specified index.
type: docs
weight: 79
url: /cpp/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(**int32_t**, [System::String](../../../system/string/), [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>, [System::Drawing::PointF](../../../system.drawing/pointf/), [System::DateTime](../../../system/datetime/)) method


Insert new comment to a collection at the specified index.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of the element in a collection at which comment should be inserted. |
| text | [System::String](../../../system/string/) | Plain text of a new comment. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in a presentation where to add a new comment. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position on a slide where to add a new comment. |
| creationTime | [System::DateTime](../../../system/datetime/) | Time of a comment creation. |

### Return Value

Inserted comment.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
