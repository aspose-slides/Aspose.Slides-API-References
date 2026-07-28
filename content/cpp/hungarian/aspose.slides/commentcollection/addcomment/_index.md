---
title: AddComment()
second_title: Aspose.Slides C++ API referencia
description: Új megjegyzést ad a gyűjtemény végéhez.
type: docs
weight: 53
url: /hu/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metódus

Új megjegyzést ad a gyűjtemény végéhez.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Az új megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) egy prezentációban, ahol új megjegyzést kell hozzáadni. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | A dia azon pozíciója, ahová új megjegyzést kell hozzáadni. |
| creationTime | [System::DateTime](../../../system/datetime/) | A megjegyzés létrehozásának időpontja. |

### Visszatérési érték

Hozzáadott megjegyzés.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IComment](../../icomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [CommentCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)