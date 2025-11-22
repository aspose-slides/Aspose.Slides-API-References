---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API Reference
description: Returns all slide comments added by specific author.
type: docs
weight: 118
url: /aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) method


Returns all slide comments added by specific author.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Author of comments to find or null to return all comments. |

### Return Value

Array of [IComment](../../icomment/).

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentAuthor](../../icommentauthor/)
* Class [ISlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)