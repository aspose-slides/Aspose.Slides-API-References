---
title: InsertModernComment()
second_title: Справочник API Aspose.Slides для C++
description: Вставить новый современный комментарий в коллекцию по указанному индексу.
type: docs
weight: 92
url: /ru/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) метод

Вставить новый современный комментарий в коллекцию по указанному индексу.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс элемента в коллекции, в который следует вставить современный комментарий. |
| text | [System::String](../../../system/string/) | Обычный текст нового современного комментария. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) в презентации, где нужно добавить новый современный комментарий. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) на слайде, к которому привязан новый современный комментарий. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Позиция на слайде, где нужно добавить новый современный комментарий. |
| creationTime | [System::DateTime](../../../system/datetime/) | Время создания современного комментария. |

### Возвращаемое значение

Вставленный современный комментарий.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IModernComment](../../imoderncomment/)
* Класс [String](../../../system/string/)
* Класс [ISlide](../../islide/)
* Класс [IShape](../../ishape/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [DateTime](../../../system/datetime/)
* Класс [CommentCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)