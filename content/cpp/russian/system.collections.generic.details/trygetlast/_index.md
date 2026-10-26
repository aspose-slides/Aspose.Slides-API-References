---
title: TryGetLast()
second_title: Aspose.Slides для C++ справочник API
description: Пытается получить последний элемент коллекции.
type: docs
weight: 261
url: /ru/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) функция


Пытается получить последний элемент коллекции.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов коллекции. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Коллекция, из которой необходимо получить элемент. |
| found | **bool**\& | Выходной параметр. Возвращает true, если коллекция содержит хотя бы один элемент. В противном случае возвращается false. |

### Возвращаемое значение

Возвращает последний элемент коллекции. Если коллекция пуста, будет возвращено значение по умолчанию типа.

## См. также

* Класс [IEnumerable](../../system.collections.generic/ienumerable/)
* Пространство имён [System::Collections::Generic::Details](../)
* Библиотека [Aspose.Slides](../../)