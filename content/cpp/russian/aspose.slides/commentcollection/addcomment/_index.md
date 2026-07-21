---
title: AddComment()
second_title: Aspose.Slides для C++ справочник API
description: Добавить новый комментарий в конец коллекции.
type: docs
weight: 53
url: /ru/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) метод

Add new comment at the end of a collection.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Простой текст нового комментария. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) в презентации, где добавить новый комментарий. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Позиция на слайде, где добавить новый комментарий. |
| creationTime | [System::DateTime](../../../system/datetime/) | Время создания комментария. |

### Возвращаемое значение

Added comment.

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