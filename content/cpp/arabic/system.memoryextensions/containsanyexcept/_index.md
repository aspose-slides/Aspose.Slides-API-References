---
title: ContainsAnyExcept()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: يتحقق مما إذا كان مدى القراءة فقط يحتوي على أي عنصر بخلاف ثلاث قيم محددة.
type: docs
weight: 66
url: /ar/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) دالة


يتحقق مما إذا كان المدى للقراءة فقط يحتوي على أي عنصر بخلاف ثلاث قيم محددة.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في المدى |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |
| value2 | const T\& | القيمة الثالثة للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر مختلف عن القيم المحددة، false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) دالة


يتحقق مما إذا كان المدى القابل للتعديل يحتوي على أي عنصر بخلاف ثلاث قيم محددة.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في المدى |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى القابل للتعديل للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |
| value2 | const T\& | القيمة الثالثة للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر مختلف عن القيم المحددة، false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة


يتحقق مما إذا كان المدى للقراءة فقط يحتوي على أي عنصر بخلاف قيمتين محددتين.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في المدى |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر مختلف عن القيم المحددة، false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) دالة


يتحقق مما إذا كان المدى القابل للتعديل يحتوي على أي عنصر بخلاف قيمتين محددتين.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في المدى |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى القابل للتعديل للبحث فيه |
| value0 | const T\& | القيمة الأولى للاستبعاد |
| value1 | const T\& | القيمة الثانية للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر مختلف عن القيم المحددة، false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) دالة


يتحقق مما إذا كان المدى للقراءة فقط يحتوي على أي عنصر بخلاف قيمة محددة.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في المدى |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى للبحث فيه |
| value | const T\& | القيمة للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر مختلف عن القيمة المحددة، false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) دالة


يتحقق مما إذا كان المدى القابل للتعديل يحتوي على أي عنصر بخلاف قيمة محددة.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في المدى |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى القابل للتعديل للبحث فيه |
| value | const T\& | القيمة للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر مختلف عن القيمة المحددة، false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة


يتحقق مما إذا كان المدى للقراءة فقط يحتوي على أي عنصر بخلاف تلك الموجودة في مدى آخر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في الأمدات |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى للبحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | مدى القيم للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر غير موجود في values، false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة


يتحقق مما إذا كان المدى القابل للتعديل يحتوي على أي عنصر بخلاف تلك الموجودة في مدى للقراءة فقط.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع الخاص بالعناصر في الأمدات |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى القابل للتعديل للبحث فيه |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | مدى القراءة فقط للقيم للاستبعاد |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر غير موجود في values، false otherwise

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)