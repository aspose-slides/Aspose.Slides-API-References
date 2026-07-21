---
title: FindIndex()
second_title: Справочник API Aspose.Slides для C++
description: Ищет первый элемент в указанном массиве, который удовлетворяет условиям заданного предиката.
type: docs
weight: 638
url: /ru/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) метод

Ищет первый элемент в указанном массиве, который удовлетворяет условиям заданного предиката.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) для поиска элемента в |
| match | [System::Predicate](../../predicate/)\<T\> | Предикат, определяющий условия для сопоставления элементов массива |

### Возвращаемое значение

Индекс первого элемента в массиве, который удовлетворяет условиям, определённым предикатом, иначе -1

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)