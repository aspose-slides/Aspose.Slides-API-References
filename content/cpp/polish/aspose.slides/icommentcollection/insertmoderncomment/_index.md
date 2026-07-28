---
title: InsertModernComment()
second_title: Aspose.Slides dla C++ – referencja API
description: Wstaw nowy nowoczesny komentarz do kolekcji pod określonym indeksem.
type: docs
weight: 53
url: /pl/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

Wstaw nowy nowoczesny komentarz do kolekcji pod określonym indeksem.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks elementu w kolekcji, pod którym powinien zostać wstawiony nowoczesny komentarz. |
| text | [System::String](../../../system/string/) | Czysty tekst nowego nowoczesnego komentarza. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) w prezentacji, w której ma zostać dodany nowy nowoczesny komentarz. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) na slajdzie, z którym powiązany jest nowy nowoczesny komentarz. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozycja na slajdzie, w której ma zostać dodany nowy nowoczesny komentarz. |
| creationTime | [System::DateTime](../../../system/datetime/) | Czas utworzenia nowego nowoczesnego komentarza. |

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
* Klasa [ICommentCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)