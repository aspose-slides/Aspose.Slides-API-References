---
title: AddComment()
second_title: Aspose.Slides pro C++ - reference API
description: Přidá nový komentář na konec kolekce.
type: docs
weight: 53
url: /cs/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metoda


Přidá nový komentář na konec kolekce.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Prostý text nového komentáře. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) v prezentaci, kde se má přidat nový komentář. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozice na snímku, kde se má přidat nový komentář. |
| creationTime | [System::DateTime](../../../system/datetime/) | Čas vytvoření komentáře. |

### Návratová hodnota

Přidaný komentář.

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