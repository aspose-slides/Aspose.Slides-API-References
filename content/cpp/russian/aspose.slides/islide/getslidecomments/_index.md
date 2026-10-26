---
title: GetSlideComments()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает все комментарии к слайду, добавленные определённым автором.
type: docs
weight: 118
url: /ru/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) метод

Возвращает все комментарии к слайду, добавленные определённым автором.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Автор комментариев для поиска или null, чтобы вернуть все комментарии. |

### Возвращаемое значение

Массив [IComment](../../icomment/).

## См. также

* Типedef [ArrayPtr](../../../system/arrayptr/)
* Типedef [SharedPtr](../../../system/sharedptr/)
* Класс [IComment](../../icomment/)
* Класс [ICommentAuthor](../../icommentauthor/)
* Класс [ISlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)