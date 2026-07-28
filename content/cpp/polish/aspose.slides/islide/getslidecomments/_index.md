---
title: GetSlideComments()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca wszystkie komentarze slajdów dodane przez konkretnego autora.
type: docs
weight: 118
url: /pl/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metoda

Zwraca wszystkie komentarze slajdów dodane przez określonego autora.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor komentarzy do znalezienia lub null, aby zwrócić wszystkie komentarze. |

### Wartość zwracana

Tablica [IComment](../../icomment/).

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IComment](../../icomment/)
* Klasa [ICommentAuthor](../../icommentauthor/)
* Klasa [ISlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)