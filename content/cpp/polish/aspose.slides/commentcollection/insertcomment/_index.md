---
title: InsertComment()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstaw nowy komentarz do kolekcji w określonym indeksie.
type: docs
weight: 79
url: /pl/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metoda


Wstaw nowy komentarz do kolekcji w określonym indeksie.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks elementu w kolekcji, w którym należy wstawić komentarz. |
| text | [System::String](../../../system/string/) | Czysty tekst nowego komentarza. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) w prezentacji, w której ma zostać dodany nowy komentarz. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozycja na slajdzie, w której ma zostać dodany nowy komentarz. |
| creationTime | [System::DateTime](../../../system/datetime/) | Czas utworzenia komentarza. |

## Wartość zwracana

Wstawiony komentarz.

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