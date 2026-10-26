---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides для C++ API Справка
description: Проверяет, содержит ли только для чтения span любой элемент за пределами указанного диапазона.
type: docs
weight: 79
url: /ru/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция

Проверяет, содержит ли только для чтения span любой элемент за пределами указанного диапазона.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span (must be comparable) |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound (inclusive) |
| highInclusive | const T\& | The upper bound (inclusive) |

### Возвращаемое значение

true if any element outside the range is found, false otherwise

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) функция

Проверяет, содержит ли изменяемый span любой элемент за пределами указанного диапазона.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span (must be comparable) |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| lowInclusive | const T\& | The lower bound (inclusive) |
| highInclusive | const T\& | The upper bound (inclusive) |

### Возвращаемое значение

true if any element outside the range is found, false otherwise

## См. также

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)