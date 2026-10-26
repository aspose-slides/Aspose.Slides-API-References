---
title: LINQ_Count()
second_title: Aspose.Slides для C++ API Reference
description: Возвращает количество элементов в последовательности (рассчитывается путем прямого подсчёта).
type: docs
weight: 118
url: /ru/system.collections.generic/ienumerable/linq_count/
---
## IEnumerable::LINQ_Count() метод

Возвращает количество элементов в последовательности (рассчитывается путем прямого подсчёта).

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count()
```

### Возвращаемое значение

Количество элементов в последовательности.

## IEnumerable::LINQ_Count(const Func\<T, bool\>\&) метод

Возвращает количество элементов в последовательности, которые удовлетворяют указанному условию.

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count(const Func<T, bool> &predicate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| predicate | const [Func](../../../system/func/)\<T, **bool**\>\& | Функция для проверки каждого элемента на соответствие условию. |

### Возвращаемое значение

Количество элементов в последовательности, которые удовлетворяют указанному условию.

## См. также

* Класс [IEnumerable](../)
* Класс [Func](../../../system/func/)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)