---
title: InsertComment()
second_title: Aspose.Slides C++ API referencia
description: Új megjegyzést szúr be egy gyűjteménybe a megadott indexen.
type: docs
weight: 79
url: /hu/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


Új megjegyzést szúr be egy gyűjteménybe a megadott indexen.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az elem indexe a gyűjteményben, ahol a megjegyzést be kell szúrni. |
| text | [System::String](../../../system/string/) | Az új megjegyzés egyszerű szövege. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A [Slide](../../slide/) a prezentációban, ahová az új megjegyzést hozzá kell adni. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozíció a dián, ahol az új megjegyzést hozzá kell adni. |
| creationTime | [System::DateTime](../../../system/datetime/) | A megjegyzés létrehozásának ideje. |

### Visszatérési érték

Beszúrt megjegyzés.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IComment](../../icomment/)
* Osztály [String](../../../system/string/)
* Osztály [ISlide](../../islide/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [CommentCollection](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)