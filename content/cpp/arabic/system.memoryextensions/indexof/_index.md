---
title: IndexOf()
second_title: Aspose.Slides لـ C++ مرجع API
description: يجد موضع قيمة ReadOnlySpan<T> في ReadOnlySpan<T> آخر
type: docs
weight: 144
url: /ar/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يجد موضع قيمة ReadOnlySpan<T> في ReadOnlySpan<T> آخر

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث عنه |

### قيمة الإرجاع

المؤشر الصفري للظهور الأول، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) دالة

يجد موضع قيمة فردية في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value | const T\& | القيمة للبحث عنها |

### قيمة الإرجاع

المؤشر الصفري للظهور الأول، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يجد موضع قيمة ReadOnlySpan<T> في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث عنه |

### قيمة الإرجاع

المؤشر الصفري للظهور الأول، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) دالة

يجد موضع قيمة فردية في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| value | const T\& | القيمة للبحث عنها |

### قيمة الإرجاع

المؤشر الصفري للظهور الأول، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) دالة

يجد موضع قيمة ReadOnlySpan<char16_t> في ReadOnlySpan<char16_t> باستخدام StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | النطاق للبحث فيه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | القيمة للبحث عنها |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقارنة السلسلة لاستخدامه |

### قيمة الإرجاع

المؤشر الصفري للظهور الأول، أو -1 إذا لم يُعثر عليه

## أنظر أيضًا

* تعداد [StringComparison](../../system/stringcomparison/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* نطاق الاسم [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)