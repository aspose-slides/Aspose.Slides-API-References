---
title: InsertComment()
second_title: Aspose.Slides a C++ API hivatkozás
description: Új megjegyzés beszúrása egy gyűjteménybe a megadott indexen.
type: docs
weight: 40
url: /hu/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

Új megjegyzés beszúrása egy gyűjteménybe a megadott indexen.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az elem indexe a gyűjteményben, amelyhez a megjegyzést be kell szúrni. |
| text | [System::String](../../../system/string/) | Az új megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) egy prezentációban, ahol új megjegyzést adunk hozzá. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozíció a dián, ahol új megjegyzést adunk hozzá. |
| creationTime | [System::DateTime](../../../system/datetime/) | Megjegyzés létrehozásának időpontja. |

### Visszatérési érték

A beszúrt megjegyzés.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IComment](../../icomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [ICommentCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)