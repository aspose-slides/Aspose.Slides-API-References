---
title: AddComment()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový komentář na konec kolekce.
type: docs
weight: 14
url: /cs/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


Přidejte nový komentář na konec kolekce.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Prostý text nového komentáře. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) v prezentaci, kde přidat nový komentář. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozice na snímku, kde přidat nový komentář. |
| creationTime | [System::DateTime](../../../system/datetime/) | Čas vytvoření komentáře. |

### Návratová hodnota

Přidaný komentář.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)