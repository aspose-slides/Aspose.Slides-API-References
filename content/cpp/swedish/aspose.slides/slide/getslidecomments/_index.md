---
title: GetSlideComments()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alla bildkommentarer som lagts till av en specifik författare.
type: docs
weight: 209
url: /sv/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metod


Returnerar alla bildkommentarer som lagts till av en specifik författare.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Författare till kommentarer att hitta eller null för att returnera alla kommentarer. |

### Returvärde

Array av [Comment](../../comment/).

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComment](../../icomment/)
* Klass [ICommentAuthor](../../icommentauthor/)
* Klass [Slide](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)