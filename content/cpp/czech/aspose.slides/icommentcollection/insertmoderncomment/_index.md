---
title: InsertModernComment()
second_title: Aspose.Slides pro referenci API C++
description: Vložit nový moderní komentář do kolekce na určeném indexu.
type: docs
weight: 53
url: /cs/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metoda

Vložit nový moderní komentář do kolekce na určený index.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index prvku v kolekci, na který má být moderní komentář vložen. |
| text | [System::String](../../../system/string/) | Surový text nového moderního komentáře. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) v prezentaci, kde se má přidat nový moderní komentář. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) na snímku, ke kterému je nový moderní komentář připojen. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozice na snímku, kde se má přidat nový moderní komentář. |
| creationTime | [System::DateTime](../../../system/datetime/) | Čas vytvoření moderního komentáře. |

### Návratová hodnota

Vložený moderní komentář.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IModernComment](../../imoderncomment/)
* Třída [String](../../../system/string/)
* Třída [ISlide](../../islide/)
* Třída [IShape](../../ishape/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [DateTime](../../../system/datetime/)
* Třída [ICommentCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)