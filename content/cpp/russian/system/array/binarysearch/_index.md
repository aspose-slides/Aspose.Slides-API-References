---
title: BinarySearch()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет двоичный поиск в отсортированном массиве.
type: docs
weight: 612
url: /ru/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Выполняет двоичный поиск в отсортированном массиве.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Отсортированный массив, в котором выполнять поиск |
| item | const T\& | Элемент, который нужно найти |

### Возвращаемое значение

Индекс найденного элемента, если он найден; иначе отрицательное целое число, являющееся побитовым дополнением индекса следующего элемента, большего искомого, или, если большего элемента нет, побитовым дополнением количества элементов в массиве.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method


НЕ РЕАЛИЗОВАНО.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [Array](../)
* Класс [IComparer](../../../system.collections.generic/icomparer/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)