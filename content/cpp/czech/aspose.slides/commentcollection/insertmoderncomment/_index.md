---
title: InsertModernComment()
second_title: Aspose.Slides pro C++ API Reference
description: Vloží nový moderní komentář do kolekce na zadaném indexu.
type: docs
weight: 92
url: /cs/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metoda

Vloží nový moderní komentář do kolekce na zadaném indexu.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index prvku v kolekci, do které má být moderní komentář vložen. |
| text | [System::String](../../../system/string/) | Prostý text nového moderního komentáře. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) v prezentaci, kde se má přidat nový moderní komentář. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) na snímku, ke kterému je nový moderní komentář přiřazen. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozice na snímku, kde se má přidat nový moderní komentář. |
| creationTime | [System::DateTime](../../../system/datetime/) | Čas vytvoření moderního komentáře. |

### Návratová hodnota

Vložený moderní komentář.

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IModernComment](../../imoderncomment/)
* Třída [String](../../../system/string/)
* Třída [ISlide](../../islide/)
* Třída [IShape](../../ishape/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [DateTime](../../../system/datetime/)
* Třída [CommentCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)