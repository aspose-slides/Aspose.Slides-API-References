---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает первый элемент последовательности или значение по умолчанию, если последовательность пуста.
type: docs
weight: 66
url: /ru/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() метод

Возвращает первый элемент последовательности или значение по умолчанию, если последовательность пуста.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### Возвращаемое значение

Первый элемент в последовательности или значение, сконструированное по умолчанию, если последовательность пуста.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) метод

Возвращает первый элемент последовательности, удовлетворяющий условию, или значение по умолчанию, если такой элемент не найден.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Функция для проверки каждого элемента на условие. |

### Возвращаемое значение

default(T), если source пуст или если ни один элемент не проходит проверку, указанную предикатом; в противном случае — первый элемент в source, проходящий проверку, указанную предикатом.

## Смотрите также

* Класс [IEnumerable](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)