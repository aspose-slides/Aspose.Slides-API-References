---
title: AddModernComment()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Dodaj nowy nowoczesny komentarz na końcu kolekcji.
type: docs
weight: 66
url: /pl/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metoda


Dodaj nowy nowoczesny komentarz na końcu kolekcji.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Zwykły tekst nowego nowoczesnego komentarza. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) w prezentacji, w której zostanie dodany nowy nowoczesny komentarz. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) na slajdzie, do którego jest powiązany nowy nowoczesny komentarz. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozycja na slajdzie, w której dodaje się nowy nowoczesny komentarz. |
| creationTime | [System::DateTime](../../../system/datetime/) | Czas utworzenia nowoczesnego komentarza. |

### Wartość zwracana

Dodany nowoczesny komentarz.
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




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
* Biblioteka [Aspose.Slides](../../../)