---
title: InsertComment()
second_title: Справочник API Aspose.Slides для C++
description: Вставить новый комментарий в коллекцию по указанному индексу.
type: docs
weight: 40
url: /ru/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) метод

Вставить новый комментарий в коллекцию по указанному индексу.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс элемента в коллекции, в который следует вставить комментарий. |
| text | [System::String](../../../system/string/) | Обычный текст нового комментария. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) в презентации, где следует добавить новый комментарий. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Позиция на слайде, где следует добавить новый комментарий. |
| creationTime | [System::DateTime](../../../system/datetime/) | Время создания комментария. |

### Возвращаемое значение

Вставленный комментарий.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IComment](../../icomment/)
* Класс [String](../../../system/string/)
* Класс [ISlide](../../islide/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [DateTime](../../../system/datetime/)
* Класс [ICommentCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)