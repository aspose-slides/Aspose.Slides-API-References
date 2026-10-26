---
title: LINQ_OrderBy()
second_title: Справка API Aspose.Slides для C++
description: Сортирует элементы последовательности в порядке возрастания согласно значениям ключей, выбранным с помощью keySelector.
type: docs
weight: 209
url: /ru/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) метод


Сортирует элементы последовательности в порядке возрастания согласно значениям ключей, выбранным с помощью keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| keySelector | Функция для получения ключа из элемента. |

### Возвращаемое значение

IOrderedEnumerable, элементы которого отсортированы согласно ключу

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) метод




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Класс [Func](../../../system/func/)
* Класс [IEnumerable](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)