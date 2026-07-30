---
title: InsertComment()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vloží nový komentář do kolekce na zadaném indexu.
type: docs
weight: 79
url: /cs/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metoda

Vloží nový komentář do kolekce na zadaném indexu.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index prvku v kolekci, do které má být komentář vložen. |
| text | [System::String](../../../system/string/) | Prostý text nového komentáře. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) v prezentaci, kde má být přidán nový komentář. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozice na snímku, kde má být přidán nový komentář. |
| creationTime | [System::DateTime](../../../system/datetime/) | Čas vytvoření komentáře. |

### Návratová hodnota

Vložený komentář.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IComment](../../icomment/)
* Třída [String](../../../system/string/)
* Třída [ISlide](../../islide/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [DateTime](../../../system/datetime/)
* Třída [CommentCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)