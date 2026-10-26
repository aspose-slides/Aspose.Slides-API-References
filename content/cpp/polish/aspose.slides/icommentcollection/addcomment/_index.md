---
title: AddComment()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaj nowy komentarz na końcu kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metoda

Dodaj nowy komentarz na końcu kolekcji.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Czysty tekst nowego komentarza. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) w prezentacji, w której ma zostać dodany nowy komentarz. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozycja na slajdzie, w której ma zostać dodany nowy komentarz. |
| creationTime | [System::DateTime](../../../system/datetime/) | Czas utworzenia komentarza. |

### Wartość zwracana

Dodany komentarz.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IComment](../../icomment/)
* Klasa [String](../../../system/string/)
* Klasa [ISlide](../../islide/)
* Klasa [PointF](../../../system.drawing/pointf/)
* Klasa [DateTime](../../../system/datetime/)
* Klasa [ICommentCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)