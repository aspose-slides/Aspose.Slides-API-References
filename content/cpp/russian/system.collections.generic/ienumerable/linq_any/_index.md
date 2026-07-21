---
title: LINQ_Any()
second_title: Aspose.Slides для C++ справка API
description: Определяет, содержит ли последовательность какие-либо элементы.
type: docs
weight: 157
url: /ru/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() метод

Определяет, содержит ли последовательность какие-либо элементы.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### Возвращаемое значение

true если исходная последовательность содержит какие-либо элементы; иначе false.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) метод

Определяет, существует ли любой элемент последовательности или удовлетворяет условию.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Функция для проверки каждого элемента на соответствие условию. |

### Возвращаемое значение

true если исходная последовательность содержит какие-либо элементы; иначе false.

## См. также

* Класс [IEnumerable](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)