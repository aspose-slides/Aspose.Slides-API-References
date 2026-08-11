---
title: IndexOfAnyExcept()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعثر على فهرس العنصر الأول الذي لا يساوي القيمة المحددة في ReadOnlySpan<T>
type: docs
weight: 170
url: /ar/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي القيمة المحددة في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي أيًا من القيمتين المحددتين في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي أيًا من القيم الثلاث المحددة في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |
| value2 | const T\& | The third value to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي القيمة المحددة في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي أيًا من القيمتين المحددتين في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي أيًا من القيم الثلاث المحددة في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |
| value2 | const T\& | The third value to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي أي قيمة في مجموعة من القيم.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يعثر على فهرس العنصر الأول الذي لا يساوي أي قيمة في مجموعة من القيم في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to exclude from the search |

### قيمة الإرجاع

The zero-based index of the first non-matching element, or -1 if not found

## انظر أيضًا

* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* نطاق أسماء [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)