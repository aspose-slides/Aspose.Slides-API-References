---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API Reference
description: Returns all slide comments added by specific author.
type: docs
weight: 209
url: /cpp/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) method


Returns all slide comments added by specific author.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Author of comments to find or null to return all comments. |

### Return Value

Array of [Comment](../../comment/).

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentAuthor](../../icommentauthor/)
* Class [Slide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)