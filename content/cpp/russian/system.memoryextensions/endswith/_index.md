---
title: EndsWith()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, заканчивается ли ReadOnlySpan<T> одним значением.
type: docs
weight: 131
url: /ru/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) функция

Определяет, заканчивается ли ReadOnlySpan<T> одним значением.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, который необходимо проверить |
| value | const T\& | Значение, которое нужно проверить в конце span |

### Возвращаемое значение

true, если span заканчивается значением, иначе false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Определяет, заканчивается ли ReadOnlySpan<T> другим ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, который необходимо проверить |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, который нужно проверить в конце целевого span |

### Возвращаемое значение

true, если span заканчивается значением, иначе false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Определяет, заканчивается ли Span<T> ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, который необходимо проверить |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, который нужно проверить в конце целевого span |

### Возвращаемое значение

true, если span заканчивается значением, иначе false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) функция

Определяет, заканчивается ли ReadOnlySpan<T> Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, который необходимо проверить |
| value | const [Span](../../system/span/)\<T\>\& | Span, который нужно проверить в конце целевого span |

### Возвращаемое значение

true, если span заканчивается значением, иначе false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) функция

Определяет, заканчивается ли Span<T> другим Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, который необходимо проверить |
| value | const [Span](../../system/span/)\<T\>\& | Span, который нужно проверить в конце целевого span |

### Возвращаемое значение

true, если span заканчивается значением, иначе false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) функция

Определяет, заканчивается ли ReadOnlySpan<char16_t> указанным значением с использованием StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span, который необходимо проверить |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Значение, которое нужно проверить в конце span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Тип сравнения строк, который следует использовать |

### Возвращаемое значение

true, если span заканчивается значением, иначе false

## См. также

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)