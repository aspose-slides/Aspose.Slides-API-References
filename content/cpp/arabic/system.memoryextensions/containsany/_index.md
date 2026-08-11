---
title: ContainsAny()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق مما إذا كان نطاق قراءة فقط يحتوي على أي من قيمتين.
type: docs
weight: 53
url: /ar/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة


يتحقق مما إذا كان نطاق للقراءة فقط يحتوي على أي من قيمتين.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المُعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |

### قيمة الإرجاع

true إذا تم العثور على أي من القيم في span ، false غير ذلك

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) دالة


يتحقق مما إذا كان نطاق للقراءة فقط يحتوي على أي من ثلاث قيم.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المُعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |
| value2 | const T\& | القيمة الثالثة للبحث عنها |

### قيمة الإرجاع

true إذا تم العثور على أي من القيم في span ، false غير ذلك

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) دالة


يتحقق مما إذا كان نطاق قابل للتعديل يحتوي على أي من قيمتين.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```


### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المُعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل للبحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |

### قيمة الإرجاع

true إذا تم العثور على أي من القيم في span ، false غير ذلك

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) دالة


يتحقق مما إذا كان نطاق قابل للتعديل يحتوي على أي من ثلاث قيم.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المُعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل للبحث فيه |
| value0 | const T\& | القيمة الأولى للبحث عنها |
| value1 | const T\& | القيمة الثانية للبحث عنها |
| value2 | const T\& | القيمة الثالثة للبحث عنها |

### قيمة الإرجاع

true إذا تم العثور على أي من القيم في span ، false غير ذلك

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة


يتحقق مما إذا كان نطاق للقراءة فقط يحتوي على أي قيمة من نطاق آخر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### المُعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي يحتوي على القيم للبحث عنها |

### قيمة الإرجاع

true إذا تم العثور على أي قيمة من values في span ، false غير ذلك

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة


يتحقق مما إذا كان نطاق قابل للتعديل يحتوي على أي قيمة من نطاق للقراءة فقط.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### المُعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل للبحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للقراءة فقط الذي يحتوي على القيم للبحث عنها |

### قيمة الإرجاع

true إذا تم العثور على أي قيمة من values في span ، false غير ذلك

## أنظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* مساحة الاسم [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)