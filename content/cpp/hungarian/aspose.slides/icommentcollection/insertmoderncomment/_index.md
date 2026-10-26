---
title: InsertModernComment()
second_title: Aspose.Slides C++ API Referenciája
description: Új modern megjegyzést szúr be egy gyűjteménybe a megadott indexnél.
type: docs
weight: 53
url: /hu/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Új modern megjegyzést szúr be egy gyűjteménybe a megadott indexnél.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az elem indexe a gyűjteményben, ahová a modern megjegyzést be kell szúrni. |
| text | [System::String](../../../system/string/) | Az új modern megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) egy prezentációban, ahová az új modern megjegyzést hozzá kell adni. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) egy dián, amelyhez az új modern megjegyzés tartozik. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozíció a dián, ahová az új modern megjegyzést kell elhelyezni. |
| creationTime | [System::DateTime](../../../system/datetime/) | A modern megjegyzés létrehozásának időpontja. |

### Visszatérési érték

A beszúrt modern megjegyzés.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IModernComment](../../imoderncomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [IShape](../../ishape/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [ICommentCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)