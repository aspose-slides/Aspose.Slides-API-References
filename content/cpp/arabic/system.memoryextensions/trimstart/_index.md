---
title: TrimStart()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقص العنصر المحدد من بداية نطاق مكتوب بنوع محدد.
type: docs
weight: 391
url: /ar/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) دالة

يقص العنصر المحدد من بداية نطاق مكتوب بنوع محدد.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي سيتم قصه |
| trimElement | const T\& | العنصر الذي سيتم قصه |

### قيمة الإرجاع

نطاق جديد مع قص العنصر المحدد من البداية

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) دالة

يقص العنصر المحدد من بداية نطاق مكتوب قابل للتعديل.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الذي سيتم قصه |
| trimElement | const T\& | العنصر الذي سيتم قصه |

### قيمة الإرجاع

نطاق جديد مع قص العنصر المحدد من البداية

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يقص العناصر المحددة من بداية نطاق مكتوب.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي سيتم قصه |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | العناصر التي سيتم قصها |

### قيمة الإرجاع

نطاق جديد مع قص العناصر المحددة من البداية

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يقص العناصر المحددة من بداية نطاق مكتوب قابل للتعديل.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الذي سيتم قصه |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | العناصر التي سيتم قصها |

### قيمة الإرجاع

نطاق جديد مع قص العناصر المحددة من البداية

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) دالة

يقص أحرف المسافة البيضاء من بداية نطاق حرفي.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | النطاق الحرفي الذي سيتم قصه |

### قيمة الإرجاع

نطاق جديد مع قص الأحرف البيضاء من البداية

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) دالة

يقص أحرف المسافة البيضاء من بداية نطاق حرفي قابل للتعديل.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | النطاق الحرفي القابل للتعديل الذي سيتم قصه |

### قيمة الإرجاع

نطاق جديد مع قص الأحرف البيضاء من البداية

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) دالة

يقص الحرف المحدد من بداية نطاق حرفي.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | النطاق الحرفي الذي سيتم قصه |
| trimchar | char16_t | الحرف الذي سيتم قصه |

### قيمة الإرجاع

نطاق جديد مع قص الحرف المحدد من البداية

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) دالة

يقص الحرف المحدد من بداية نطاق حرفي قابل للتعديل.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | النطاق الحرفي القابل للتعديل الذي سيتم قصه |
| trimchar | char16_t | الحرف الذي سيتم قصه |

### قيمة الإرجاع

نطاق جديد مع قص الحرف المحدد من البداية

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) دالة

يقص الأحرف المحددة من بداية نطاق حرفي.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | النطاق الحرفي الذي سيتم قصه |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | الأحرف التي سيتم قصها |

### قيمة الإرجاع

نطاق جديد مع قص الأحرف المحددة من البداية

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) دالة

يقص الأحرف المحددة من بداية نطاق حرفي قابل للتعديل.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | النطاق الحرفي القابل للتعديل الذي سيتم قصه |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | الأحرف التي سيتم قصها |

### قيمة الإرجاع

نطاق جديد مع قص الأحرف المحددة من البداية

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)