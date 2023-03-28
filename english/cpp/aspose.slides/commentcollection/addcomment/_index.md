---
title: AddComment()
second_title: Aspose.Slides for C++ API Reference
description: Add new comment at the end of a collection.
type: docs
weight: 53
url: /cpp/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment([System::String](../../../system/string/), [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>, [System::Drawing::PointF](../../../system.drawing/pointf/), [System::DateTime](../../../system/datetime/)) method


Add new comment at the end of a collection.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Plain text of a new comment. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in a presentation where to add a new comment. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position on a slide where to add a new comment. |
| creationTime | [System::DateTime](../../../system/datetime/) | Time of a comment creation. |

### Return Value

Added comment.

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
