---
title: GetSlideComments()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja az adott szerző által hozzáadott összes diakommentet.
type: docs
weight: 118
url: /hu/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metódus

Visszaadja az adott szerző által hozzáadott összes diakommentet.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | A megtalálandó kommentek szerzője, vagy null, ha az összes kommentet szeretné visszakapni. |

### Visszatérési érték

A [IComment](../../icomment/) tömb.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentAuthor](../../icommentauthor/)
* Class [ISlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)