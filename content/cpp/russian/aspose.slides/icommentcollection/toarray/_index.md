---
title: ToArray()
second_title: Aspose.Slides для C++ справочника API
description: Создаёт и возвращает массив со всеми комментариями.
type: docs
weight: 66
url: /ru/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() метод


Создает и возвращает массив со всеми комментариями.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```


### Возвращаемое значение

Массив [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) метод


Создает и возвращает массив со всеми комментариями из указанного диапазона.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **int32_t** | Индекс первого комментария, который необходимо вернуть. |
| count | **int32_t** | Количество комментариев, которые необходимо вернуть. |

### Возвращаемое значение

Массив [IComment](../../icomment/).

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IComment](../../icomment/)
* Класс [ICommentCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)