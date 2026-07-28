---
title: InsertModernComment()
second_title: Aspose.Slides dla interfejsu API C++
description: Wstaw nowy nowoczesny komentarz do kolekcji w określonym indeksie.
type: docs
weight: 92
url: /pl/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metoda

Wstaw nowy nowoczesny komentarz do kolekcji w określonym indeksie.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks elementu w kolekcji, w którym powinien zostać wstawiony nowoczesny komentarz. |
| text | [System::String](../../../system/string/) | Zwykły tekst nowego nowoczesnego komentarza. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) w prezentacji, w której ma zostać dodany nowy nowoczesny komentarz. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) na slajdzie, do którego jest powiązany nowy nowoczesny komentarz. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozycja na slajdzie, w której ma zostać dodany nowy nowoczesny komentarz. |
| creationTime | [System::DateTime](../../../system/datetime/) | Czas utworzenia nowoczesnego komentarza. |

### Wartość zwracana

Wstawiony nowoczesny komentarz.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IModernComment](../../imoderncomment/)
* Klasa [String](../../../system/string/)
* Klasa [ISlide](../../islide/)
* Klasa [IShape](../../ishape/)
* Klasa [PointF](../../../system.drawing/pointf/)
* Klasa [DateTime](../../../system/datetime/)
* Klasa [CommentCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)