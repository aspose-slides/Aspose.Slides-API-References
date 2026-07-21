---
title: Count()
second_title: Справочник API Aspose.Slides для C++
description: Подсчитывает количество вхождений значения в доступный только для чтения span.
type: docs
weight: 118
url: /ru/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) function

Подсчитывает количество вхождений значения в доступный только для чтения span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Тип элементов в span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, в котором производится поиск |
| value | const T\& | Значение для подсчёта |

### Return Value

Количество вхождений значения в span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Подсчитывает количество вхождений span внутри другого доступного только для чтения span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Тип элементов в spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, в котором производится поиск |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, вхождения которого подсчитываются |

### Return Value

Количество вхождений value в span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) function

Подсчитывает количество вхождений отдельного значения в Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Тип элементов в span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, в котором производится поиск |
| value | const T\& | Значение, вхождения которого подсчитываются |

### Return Value

Количество вхождений значения в span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Подсчитывает количество вхождений ReadOnlySpan<T> в Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Тип элементов в spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, в котором производится поиск |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, содержащий значения, вхождения которых подсчитываются |

### Return Value

Количество вхождений value span в целевом span

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)