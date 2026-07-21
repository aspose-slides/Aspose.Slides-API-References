---
title: FindAll()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает все элементы, которые соответствуют условиям, определённым указанным предикатом.
type: docs
weight: 664
url: /ru/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) метод

Возвращает все элементы, которые соответствуют условиям, определённым указанным предикатом.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) для поиска элементов в |
| match | [System::Predicate](../../predicate/)\<T\> | Предикат, определяющий условия, которым должны соответствовать элементы массива |

### Возвращаемое значение

Объект [Array](../), содержащий все элементы, которые соответствуют условиям, определённым указанным предикатом, если они найдены; в противном случае — пустой [Array](../).

## См. также

* Типовое определение [ArrayPtr](../../arrayptr/)
* Типовое определение [Predicate](../../predicate/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)