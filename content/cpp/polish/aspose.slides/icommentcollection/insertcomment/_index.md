---
title: InsertComment()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wstaw nowy komentarz do kolekcji w określonym indeksie.
type: docs
weight: 40
url: /pl/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metoda


Wstaw nowy komentarz do kolekcji w określonym indeksie.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks elementu w kolekcji, w którym powinien być wstawiony komentarz. |
| text | [System::String](../../../system/string/) | Zwykły tekst nowego komentarza. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) w prezentacji, w której dodać nowy komentarz. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozycja na slajdzie, w której dodać nowy komentarz. |
| creationTime | [System::DateTime](../../../system/datetime/) | Czas utworzenia komentarza. |

### Wartość zwracana

Wstawiony komentarz.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IComment](../../icomment/)
* Klasa [String](../../../system/string/)
* Klasa [ISlide](../../islide/)
* Klasa [PointF](../../../system.drawing/pointf/)
* Klasa [DateTime](../../../system/datetime/)
* Klasa [ICommentCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)