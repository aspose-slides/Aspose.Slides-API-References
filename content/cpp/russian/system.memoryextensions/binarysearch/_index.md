---
title: BinarySearch()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет двоичный поиск по отсортированному диапазону.
type: docs
weight: 14
url: /ru/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) функция


Выполняет двоичный поиск по отсортированному диапазону.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Возвращаемое значение

Index of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) функция


Выполняет двоичный поиск по отсортированному диапазону с использованием пользовательского сравнивателя.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Возвращаемое значение

Index of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) функция


Выполняет двоичный поиск по изменяемому отсортированному диапазону.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Возвращаемое значение

Index of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) функция


Выполняет двоичный поиск по изменяемому отсортированному диапазону с использованием пользовательского сравнивателя.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Возвращаемое значение

Index of the found element, or bitwise complement of the insertion point if not found

## См. также

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)