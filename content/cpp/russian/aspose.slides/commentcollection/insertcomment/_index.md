---
title: InsertComment()
second_title: Aspose.Slides для справочника API C++
description: Вставить новый комментарий в коллекцию по указанному индексу.
type: docs
weight: 79
url: /ru/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) метод

Вставить новый комментарий в коллекцию по указанному индексу.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс элемента в коллекции, в который следует вставить комментарий. |
| text | [System::String](../../../system/string/) | Обычный текст нового комментария. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) в презентации, в которой нужно добавить новый комментарий. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Позиция на слайде, где следует добавить новый комментарий. |
| creationTime | [System::DateTime](../../../system/datetime/) | Время создания комментария. |

### Возвращаемое значение

Вставленный комментарий.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IComment](../../icomment/)
* Класс [String](../../../system/string/)
* Класс [ISlide](../../islide/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [DateTime](../../../system/datetime/)
* Класс [CommentCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)