---
title: GetSlideComments()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alla bildkommentarer som lagts till av en specifik författare.
type: docs
weight: 118
url: /sv/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metod


Returnerar alla bildkommentarer som lagts till av en specifik författare.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Författare till kommentarer att hitta eller null för att returnera alla kommentarer. |

### Returvärde

Array av [IComment](../../icomment/).

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComment](../../icomment/)
* Klass [ICommentAuthor](../../icommentauthor/)
* Klass [ISlide](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)