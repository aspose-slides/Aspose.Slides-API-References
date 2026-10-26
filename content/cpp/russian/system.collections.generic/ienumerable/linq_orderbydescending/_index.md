---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides для C++ справочник API
description: Сортирует элементы последовательности в порядке убывания согласно значениям ключа, выбранным с помощью keySelector.
type: docs
weight: 222
url: /ru/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) метод

Сортирует элементы последовательности в порядке убывания согласно значениям ключа, выбранным с помощью keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| keySelector | Функция для извлечения ключа из элемента. |

### Возвращаемое значение

IOrderedEnumerable, элементы которого отсортированы по убывающему порядку ключа

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) метод

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Класс [Func](../../../system/func/)
* Класс [IEnumerable](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)