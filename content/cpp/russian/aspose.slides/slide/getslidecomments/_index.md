---
title: GetSlideComments()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает все комментарии слайда, добавленные конкретным автором.
type: docs
weight: 209
url: /ru/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) метод

Возвращает все комментарии слайда, добавленные конкретным автором.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Автор комментариев для поиска или null для возврата всех комментариев. |

### Возвращаемое значение

Массив [Comment](../../comment/).

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IComment](../../icomment/)
* Класс [ICommentAuthor](../../icommentauthor/)
* Класс [Slide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)