---
title: LastIndexOfAnyExcept()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن الموضع الأخير لأي عنصر باستثناء ثلاث قيم محددة داخل نطاق.
type: docs
weight: 235
url: /ar/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء ثلاث قيم محددة داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |
| value2 | const T\& | القيمة الثالثة للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء ثلاث قيم محددة داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |
| value2 | const T\& | القيمة الثالثة للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء قيمتين محددتين داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء قيمتين محددتين داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء قيمة محددة داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value | const T\& | القيمة للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء قيمة محددة داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| value | const T\& | القيمة للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء قيم من تسلسل داخل نطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | تسلسل القيم للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء قيم من تسلسل داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | تسلسل القيم للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) دالة

يعثر على الموضع الأخير لأي عنصر باستثناء قيم من تسلسل قابل للتعديل داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| values | const [Span](../../system/span/)\<T\>\& | تسلسل القيم للاستبعاد |

### قيمة الإرجاع

المؤشر الصفري للعنصر الأخير غير المستبعد، أو -1 إذا لم يتم العثور عليه

## انظر أيضًا

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)