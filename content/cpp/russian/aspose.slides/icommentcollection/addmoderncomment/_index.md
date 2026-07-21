---
title: AddModernComment()
second_title: Aspose.Slides для C++ справочник API
description: Добавить новый современный комментарий в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) метод


Добавить новый современный комментарий в конец коллекции.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст нового современного комментария. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) в презентации, куда нужно добавить новый современный комментарий. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) на слайде, к которому привязан новый современный комментарий. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Позиция на слайде, куда добавить новый современный комментарий. |
| creationTime | [System::DateTime](../../../system/datetime/) | Время создания современного комментария. |

### Возвращаемое значение

Добавленный современный комментарий.
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IModernComment](../../imoderncomment/)
* Класс [String](../../../system/string/)
* Класс [ISlide](../../islide/)
* Класс [IShape](../../ishape/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [DateTime](../../../system/datetime/)
* Класс [ICommentCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)