---
title: GetSlideComments()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací všechny komentáře snímku přidané konkrétním autorem.
type: docs
weight: 118
url: /cs/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metoda


Vrací všechny komentáře snímku přidané konkrétním autorem.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor komentářů, který se má najít, nebo null pro vrácení všech komentářů. |

### Návratová hodnota

Pole typu [IComment](../../icomment/).

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IComment](../../icomment/)
* Třída [ICommentAuthor](../../icommentauthor/)
* Třída [ISlide](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)