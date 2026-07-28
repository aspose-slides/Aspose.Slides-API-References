---
title: AddComment()
second_title: Aspose.Slides C++ API referencia
description: Új megjegyzés hozzáadása a gyűjtemény végén.
type: docs
weight: 14
url: /hu/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metódus

Új megjegyzést ad a gyűjtemény végén.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Az új megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) egy prezentációban, ahol új megjegyzést adhatunk hozzá. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozíció a dián, ahol új megjegyzést adunk hozzá. |
| creationTime | [System::DateTime](../../../system/datetime/) | A megjegyzés létrehozásának időpontja. |

### Visszatérési érték

A hozzáadott megjegyzés.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IComment](../../icomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [ICommentCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)