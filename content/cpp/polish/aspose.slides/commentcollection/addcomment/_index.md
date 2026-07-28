---
title: AddComment()
second_title: Aspose.Slides dla interfejsu API C++
description: Dodaj nowy komentarz na końcu kolekcji.
type: docs
weight: 53
url: /pl/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

Dodaj nowy komentarz na końcu kolekcji.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Plain text of a new comment. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in a presentation where to add a new comment. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position on a slide where to add a new comment. |
| creationTime | [System::DateTime](../../../system/datetime/) | Time of a comment creation. |

### Wartość zwracana

Dodany komentarz.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IComment](../../icomment/)
* Klasa [String](../../../system/string/)
* Klasa [ISlide](../../islide/)
* Klasa [PointF](../../../system.drawing/pointf/)
* Klasa [DateTime](../../../system/datetime/)
* Klasa [CommentCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)