---
title: GetSlideComments()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca wszystkie komentarze slajdu dodane przez określonego autora.
type: docs
weight: 209
url: /pl/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metoda

Returns all slide comments added by specific author.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor komentarzy do wyszukania lub null, aby zwrócić wszystkie komentarze. |

### Wartość zwracana

Array of [Comment](../../comment/).

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IComment](../../icomment/)
* Klasa [ICommentAuthor](../../icommentauthor/)
* Klasa [Slide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)