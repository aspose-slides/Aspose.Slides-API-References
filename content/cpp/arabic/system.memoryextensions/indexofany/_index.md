---
title: IndexOfAny()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد فهرس أول ظهور لأي من القيمتين المحددتين في ReadOnlySpan<T>
type: docs
weight: 157
url: /ar/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يُرجع فهرس أول ظهور لأيّ من القيمتين المحددتين في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق المراد البحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |

### قيمة الإرجاع

فهرس يبدأ من الصفر للظهور الأول، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) دالة

يُرجع فهرس أول ظهور لأيّ من القيم الثلاث المحددة في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق المراد البحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |
| value2 | const T\& | القيمة الثالثة للبحث عنها |

### قيمة الإرجاع

فهرس يبدأ من الصفر للظهور الأول، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) دالة

يُرجع فهرس أول ظهور لأيّ من القيمتين المحددتين في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق المراد البحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |

### قيمة الإرجاع

فهرس يبدأ من الصفر للظهور الأول، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) دالة

يُرجع فهرس أول ظهور لأيّ من القيم الثلاث المحددة في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق المراد البحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |
| value2 | const T\& | القيمة الثالثة للبحث عنها |

### قيمة الإرجاع

فهرس يبدأ من الصفر للظهور الأول، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يُرجع فهرس أول ظهور لأي قيمة من نطاق في ReadOnlySpan<T> آخر

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق المراد البحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي يحتوي على القيم للبحث عنها |

### قيمة الإرجاع

فهرس يبدأ من الصفر للظهور الأول، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يُرجع فهرس أول ظهور لأي قيمة من نطاق في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق المراد البحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي يحتوي على القيم للبحث عنها |

### قيمة الإرجاع

فهرس يبدأ من الصفر للظهور الأول، أو -1 إذا لم يتم العثور عليه

## راجع أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* مساحة الأسماء [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)