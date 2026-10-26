---
title: InsertModernComment()
second_title: Aspose.Slides для C++ справочник API
description: Вставить новый современный комментарий в коллекцию по указанному индексу.
type: docs
weight: 53
url: /ru/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) метод


Вставить новый современный комментарий в коллекцию по указанному индексу.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс элемента в коллекции, в который должен быть вставлен современный комментарий. |
| text | [System::String](../../../system/string/) | Простой текст нового современного комментария. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) в презентации, где нужно добавить новый современный комментарий. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) на слайде, к которому привязан новый современный комментарий. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Позиция на слайде, где нужно добавить новый современный комментарий. |
| creationTime | [System::DateTime](../../../system/datetime/) | Время создания современного комментария. |

### Возвращаемое значение

Вставленный современный комментарий.

## См. также

* Типedef [SharedPtr](../../../system/sharedptr/)
* Класс [IModernComment](../../imoderncomment/)
* Класс [String](../../../system/string/)
* Класс [ISlide](../../islide/)
* Класс [IShape](../../ishape/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [DateTime](../../../system/datetime/)
* Класс [ICommentCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)