---
title: CommonPrefixLength()
second_title: Aspose.Slides для C++ справочник API
description: Находит длину общего префикса между двумя диапазонами.
type: docs
weight: 27
url: /ru/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Находит длину общего префикса между двумя диапазонами.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый диапазон |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй диапазон |

### Возвращаемое значение

Количество совпадающих элементов в начале обоих диапазонов

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Находит длину общего префикса между изменяемым диапазоном и диапазоном только для чтения.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Изменяемый диапазон |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон только для чтения |

### Возвращаемое значение

Количество совпадающих элементов в начале обоих диапазонов

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) функция

Находит длину общего префикса между двумя изменяемыми диапазонами.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Первый изменяемый диапазон |
| other | const [Span](../../system/span/)\<T\>\& | Второй изменяемый диапазон |

### Возвращаемое значение

Количество совпадающих элементов в начале обоих диапазонов

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) функция


Находит длину общего префикса между двумя диапазонами с использованием пользовательского сравнивателя равенств.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |
| TEqualityComparer | Тип сравнивателя равенств |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый диапазон |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй диапазон |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Сравниватель равенств, используемый для сравнения элементов |

### Возвращаемое значение

Количество совпадающих элементов в начале обоих диапазонов

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) функция


Находит длину общего префикса между изменяемым диапазоном и диапазоном только для чтения с использованием пользовательского сравнивателя равенств.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |
| TEqualityComparer | Тип сравнивателя равенств |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Изменяемый диапазон |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон только для чтения |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Сравниватель равенств, используемый для сравнения элементов |

### Возвращаемое значение

Количество совпадающих элементов в начале обоих диапазонов

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) функция


Находит длину общего префикса между двумя изменяемыми диапазонами с использованием пользовательского сравнивателя равенств.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |
| TEqualityComparer | Тип сравнивателя равенств |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Первый изменяемый диапазон |
| other | const [Span](../../system/span/)\<T\>\& | Второй изменяемый диапазон |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Сравниватель равенств, используемый для сравнения элементов |

### Возвращаемое значение

Количество совпадающих элементов в начале обоих диапазонов

## См. также

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)