---
title: Trim()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بقص العنصر المحدد من الطرفين لامتداد من النوع المحدد.
type: docs
weight: 365
url: /ar/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) دالة

يقوم بقص العنصر المحدد من الطرفين لامتداد من النوع المحدد.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الامتداد |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الامتداد الذي سيتم قصّه |
| trimElement | T | العنصر الذي سيتم قصّه |

### قيمة الإرجاع

امتداد جديد مع قص العنصر المحدد من الطرفين

## System::MemoryExtensions::Trim(Span\<T\>\&, T) دالة

يقوم بقص العنصر المحدد من الطرفين لامتداد من النوع القابل للتعديل.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الامتداد |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | الامتداد القابل للتعديل الذي سيتم قصّه |
| trimElement | T | العنصر الذي سيتم قصّه |

### قيمة الإرجاع

امتداد جديد مع قص العنصر المحدد من الطرفين

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يقوم بقص العناصر المحددة من الطرفين لامتداد من النوع المحدد.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الامتداد |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الامتداد الذي سيتم قصّه |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | العناصر التي سيتم قصّها |

### قيمة الإرجاع

امتداد جديد مع قص العناصر المحددة من الطرفين

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يقوم بقص العناصر المحددة من الطرفين لامتداد من النوع القابل للتعديل.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الامتداد |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | الامتداد القابل للتعديل الذي سيتم قصّه |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | العناصر التي سيتم قصّها |

### قيمة الإرجاع

امتداد جديد مع قص العناصر المحددة من الطرفين

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) دالة

يقوم بإزالة أحرف المسافات البيضاء من الطرفين لامتداد الأحرف.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | امتداد الأحرف الذي سيتم قصّه |

### قيمة الإرجاع

امتداد جديد مع قص المسافات البيضاء من الطرفين

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) دالة

يقوم بقص أحرف المسافات البيضاء من الطرفين لامتداد أحرف قابل للتعديل.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | امتداد الأحرف القابل للتعديل الذي سيتم قصّه |

### قيمة الإرجاع

امتداد جديد مع قص المسافات البيضاء من الطرفين

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)