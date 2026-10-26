---
title: LINQ_Where()
second_title: Справочник API Aspose.Slides для C++
description: Фильтрует последовательность на основе указанного предиката.
type: docs
weight: 170
url: /ru/system.collections.generic/ienumerable/linq_where/
---
## IEnumerable::LINQ_Where(std::function\<bool(T)>) метод

Фильтрует последовательность на основе указанного предиката.

```cpp
SharedPtr<IEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_Where(std::function<bool(T)> predicate)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Функция, проверяющая каждый элемент на выполнение некоторого условия. |

### Возвращаемое значение

Объект [IEnumerable](../), содержащий отфильтрованные элементы.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IEnumerable](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)