---
title: InsertComment()
second_title: Aspose.Slides for C++ API Reference
description: Insert new comment to a collection at the specified index.
type: docs
weight: 40
url: /cpp/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


Insert new comment to a collection at the specified index.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
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
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)