---
title: TryGetFirst()
second_title: Aspose.Slides для C++ справочник API
description: Пытается получить первый элемент коллекции.
type: docs
weight: 248
url: /ru/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) функция


Пытается получить первый элемент коллекции.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов коллекции. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Коллекция, из которой необходимо получить элемент. |
| found | **bool**\& | Выходной параметр. Возвращает true, если в коллекции есть любой элемент. В противном случае возвращается false. |

### Возвращаемое значение

Возвращает первый элемент коллекции. Если коллекция пуста, возвращается значение по умолчанию для типа.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) функция


Пытается получить первый элемент коллекции, который удовлетворяет предикатной функции.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов коллекции. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Коллекция, из которой необходимо получить элемент. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Предикатная функция. |
| found | **bool**\& | Выходной параметр. Возвращает true, если в коллекции есть любой элемент. В противном случае возвращается false. |

### Возвращаемое значение

Возвращает первый элемент коллекции. Если не найден элемент, удовлетворяющий указанной предикатной функции, возвращается значение по умолчанию для типа.

## См. также

* Класс [IEnumerable](../../system.collections.generic/ienumerable/)
* Класс [Func](../../system/func/)
* Пространство имён [System::Collections::Generic::Details](../)
* Библиотека [Aspose.Slides](../../)