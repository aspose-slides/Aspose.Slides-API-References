---
title: LastIndexOfAny()
second_title: Справочник API Aspose.Slides для C++
description: Находит последнее вхождение любого из трёх указанных значений в span.
type: docs
weight: 222
url: /ru/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) функция

Находит последнее вхождение любого из трёх указанных значений в span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |
| value2 | const T\& | Третье значение для поиска |

### Возвращаемое значение

Нулевой индекс последнего вхождения или -1, если не найдено

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) функция

Находит последнее вхождение любого из трёх указанных значений в изменяемом span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |
| value2 | const T\& | Третье значение для поиска |

### Возвращаемое значение

Нулевой индекс последнего вхождения или -1, если не найдено

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция

Находит последнее вхождение любого из двух указанных значений в span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |

### Возвращаемое значение

Нулевой индекс последнего вхождения или -1, если не найдено

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) функция

Находит последнее вхождение любого из двух указанных значений в изменяемом span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |

### Возвращаемое значение

Нулевой индекс последнего вхождения или -1, если не найдено

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Находит последнее вхождение любого значения из последовательности в span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, в котором выполняется поиск |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Последовательность значений для поиска |

### Возвращаемое значение

Нулевой индекс последнего вхождения или -1, если не найдено

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Находит последнее вхождение любого значения из последовательности в изменяемом span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, в котором выполняется поиск |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Последовательность значений для поиска |

### Возвращаемое значение

Нулевой индекс последнего вхождения или -1, если не найдено

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) функция

Находит последнее вхождение любого значения из изменяемой последовательности в изменяемом span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, в котором выполняется поиск |
| values | const [Span](../../system/span/)\<T\>\& | Последовательность значений для поиска |

### Возвращаемое значение

Нулевой индекс последнего вхождения или -1, если не найдено

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)