---
title: LastIndexOfAny()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن آخر ظهور لأي من القيم الثلاث المحددة داخل نطاق.
type: docs
weight: 222
url: /ar/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


يبحث عن آخر حدوث لأي من القيم الثلاث المحددة داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث داخل |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |
| value2 | const T\& | القيمة الثالثة للبحث عنها |

### قيمة الإرجاع

الفهرس صفر-المؤشر لآخر حدوث، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function


يبحث عن آخر حدوث لأي من القيم الثلاث المحددة داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث داخل |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |
| value2 | const T\& | القيمة الثالثة للبحث عنها |

### قيمة الإرجاع

الفهرس صفر-المؤشر لآخر حدوث، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


يبحث عن آخر حدوث لأي من القيمتين المحددتين داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث داخل |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |

### قيمة الإرجاع

الفهرس صفر-المؤشر لآخر حدوث، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) function


يبحث عن آخر حدوث لأي من القيمتين المحددتين داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث داخل |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |

### قيمة الإرجاع

الفهرس صفر-المؤشر لآخر حدوث، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


يبحث عن آخر حدوث لأي قيمة من تسلسل داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث داخل |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | تسلسل القيم للبحث عنها |

### قيمة الإرجاع

الفهرس صفر-المؤشر لآخر حدوث، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


يبحث عن آخر حدوث لأي قيمة من تسلسل داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث داخل |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | تسلسل القيم للبحث عنها |

### قيمة الإرجاع

الفهرس صفر-المؤشر لآخر حدوث، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) function


يبحث عن آخر حدوث لأي قيمة من تسلسل قابل للتعديل داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```


### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | نوع العناصر في النطاق |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث داخل |
| values | const [Span](../../system/span/)\<T\>\& | تسلسل القيم للبحث عنها |

### قيمة الإرجاع

الفهرس صفر-المؤشر لآخر حدوث، أو -1 إذا لم يُعثر عليه

## أنظر أيضًا

* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* مساحة اسم [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)