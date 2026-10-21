---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes the first occurrence of the specified comment in a collection.
type: docs
weight: 92
url: /aspose.slides/icommentcollection/remove/
---
## ICommentCollection::Remove(System::SharedPtr\<IComment\>) method


Removes the first occurrence of the specified comment in a collection.

```cpp
virtual void Aspose::Slides::ICommentCollection::Remove(System::SharedPtr<IComment> comment)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comment | [System::SharedPtr](../../../system/sharedptr/)\<[IComment](../../icomment/)\> | The comment to remove from a collection. |

### Exceptions

| Exception | Description |
| --- | --- |
| [System::ArgumentNullException](../../../system/argumentnullexception/) | If comment is **null** |
| [Aspose::Slides::PptxEditException](../../pptxeditexception/) | Thrown if comment is already removed. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)