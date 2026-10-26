---
title: TrueForAll()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, удовлетворяют ли все элементы указанного массива условиям, определённым заданным предикатом.
type: docs
weight: 677
url: /ru/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) метод

Определяет, удовлетворяют ли все элементы указанного массива условиям, определённым заданным предикатом.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) элементы, которые необходимо сопоставить с условиями |
| match | [System::Predicate](../../predicate/)\<T\> | Предикат, определяющий условия, с которыми сравниваются элементы массива |

### Возвращаемое значение

true если все элементы массива arr удовлетворяют условиям, определённым предикатом match, в противном случае false

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)