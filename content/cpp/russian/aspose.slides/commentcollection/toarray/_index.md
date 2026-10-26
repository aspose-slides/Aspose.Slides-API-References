---
title: ToArray()
second_title: Справочник API Aspose.Slides для C++
description: Создает и возвращает массив со всеми комментариями.
type: docs
weight: 105
url: /ru/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() метод


Создает и возвращает массив со всеми комментариями.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Возвращаемое значение

Массив [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) метод


Создает и возвращает массив со всеми комментариями из указанного диапазона.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **int32_t** | Индекс первого комментария, который нужно вернуть. |
| count | **int32_t** | Количество комментариев, которые нужно вернуть. |

### Возвращаемое значение

Массив [Comment](../../comment/).

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IComment](../../icomment/)
* Класс [CommentCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)