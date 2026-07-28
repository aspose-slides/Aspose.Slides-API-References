---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja az adott szerző által hozzáadott összes diakommentet.
type: docs
weight: 209
url: /hu/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metódus


Visszaadja a megadott szerző által hozzáadott összes diakommentet.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | A keresett kommentek szerzője, vagy null az összes komment visszaadásához. |

### Visszatérési érték

A [Comment](../../comment/) tömbje.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IComment](../../icomment/)
* Osztály [ICommentAuthor](../../icommentauthor/)
* Osztály [Slide](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)