---
title: GetSlideComments()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací všechny komentáře snímku přidané konkrétním autorem.
type: docs
weight: 209
url: /cs/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metoda


Vrací všechny komentáře snímku přidané konkrétním autorem.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor komentářů, které se mají najít, nebo null pro vrácení všech komentářů. |

### Návratová hodnota

Pole typu [Comment](../../comment/).

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IComment](../../icomment/)
* Třída [ICommentAuthor](../../icommentauthor/)
* Třída [Slide](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)