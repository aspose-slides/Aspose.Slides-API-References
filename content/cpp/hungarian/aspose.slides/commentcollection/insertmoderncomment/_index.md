---
title: InsertModernComment()
second_title: Aspose.Slides C++ API hivatkozás
description: Új modern megjegyzést szúr be egy gyűjteménybe a megadott indexnél.
type: docs
weight: 92
url: /hu/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metódus

Új modern megjegyzést szúr be egy gyűjteménybe a megadott indexen.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az elem indexe egy gyűjteményben, ahová a modern megjegyzést be kell illeszteni. |
| text | [System::String](../../../system/string/) | Az új modern megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) egy prezentációban, ahol új modern megjegyzést adunk hozzá. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) egy dián, amelyhez az új modern megjegyzés tartozik. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozíció a dián, ahol új modern megjegyzést adunk hozzá. |
| creationTime | [System::DateTime](../../../system/datetime/) | A modern megjegyzés létrehozásának időpontja. |

### Visszatérési érték

Beszúrt modern megjegyzés.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IModernComment](../../imoderncomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [IShape](../../ishape/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [CommentCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)