---
title: AddModernComment()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Dodaj nowy nowoczesny komentarz na końcu kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Dodaj nowy nowoczesny komentarz na końcu kolekcji.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Zwykły tekst nowego nowoczesnego komentarza. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) w prezentacji, w której ma zostać dodany nowy nowoczesny komentarz. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) na slajdzie, do którego jest powiązany nowy nowoczesny komentarz. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Pozycja na slajdzie, w której ma zostać dodany nowy nowoczesny komentarz. |
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
* Class [IModernComment](../../imoderncomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [IShape](../../ishape/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)