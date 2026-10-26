---
title: Find()
second_title: Aspose.Slides для C++ справочник API
description: Ищет первый элемент в указанном массиве, который удовлетворяет условиям заданного предиката.
type: docs
weight: 651
url: /ru/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) метод

Ищет первый элемент в указанном массиве, который удовлетворяет условиям заданного предиката.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) для поиска элемента |
| match | [System::Predicate](../../predicate/)\<T\> | Предикат, определяющий условия сопоставления элементов массива |

### Возвращаемое значение

Копия первого элемента массива, который удовлетворяет условиям, определённым предикатом, иначе значение по умолчанию типа T

## См. также

* Тип [ArrayPtr](../../arrayptr/)
* Тип [Predicate](../../predicate/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)