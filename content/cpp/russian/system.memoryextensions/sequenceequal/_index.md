---
title: SequenceEqual()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, содержат ли два ReadOnlySpan одинаковые элементы в том же порядке.
type: docs
weight: 326
url: /ru/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Определяет, содержат ли два ReadOnlySpan одинаковые элементы в том же порядке.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый диапазон для сравнения |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй диапазон для сравнения |

### Возвращаемое значение

true если диапазоны имеют одинаковую длину и все элементы равны, false в противном случае

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Определяет, содержат ли [Span](../../system/span/) и [ReadOnlySpan](../../system/readonlyspan/) одинаковые элементы в том же порядке.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) для сравнения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) для сравнения |

### Возвращаемое значение

true если диапазоны имеют одинаковую длину и все элементы равны, false в противном случае

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

Определяет, содержат ли два ReadOnlySpan равные элементы с использованием пользовательского сравнивателя.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |
| TComparer | Тип объекта сравнивателя |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый диапазон для сравнения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй диапазон для сравнения |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Умный указатель на объект сравнивателя для сравнения элементов |

### Возвращаемое значение

true если диапазоны имеют одинаковую длину и comparer считает все элементы равными, false в противном случае

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

Определяет, содержат ли [Span](../../system/span/) и [ReadOnlySpan](../../system/readonlyspan/) равные элементы с использованием пользовательского сравнивателя.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |
| TComparer | Тип объекта сравнивателя |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) для сравнения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) для сравнения |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Умный указатель на объект сравнивателя для сравнения элементов |

### Возвращаемое значение

true если диапазоны имеют одинаковую длину и comparer считает все элементы равными, false в противном случае

## См. также

* Typedef [SharedPtr](../../system/sharedptr/)
* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)