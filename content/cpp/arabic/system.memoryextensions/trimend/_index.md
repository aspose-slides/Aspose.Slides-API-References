---
title: TrimEnd()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقص العنصر المحدد من نهاية نطاق مكتوب بنوع.
type: docs
weight: 378
url: /ar/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) function

يقص العنصر المحدد من نهاية النطاق المكتوب بنوع.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي سيُقص |
| trimElement | const T\& | العنصر الذي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص العنصر المحدد من النهاية

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) function

يقص العنصر المحدد من نهاية النطاق المكتوب القابل للتعديل.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الذي سيُقص |
| trimElement | const T\& | العنصر الذي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص العنصر المحدد من النهاية

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

يقص العناصر المحددة من نهاية النطاق المكتوب بنوع.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي سيُقص |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | العناصر التي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص العناصر المحددة من النهاية

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

يقص العناصر المحددة من نهاية النطاق المكتوب القابل للتعديل.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الذي سيُقص |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | العناصر التي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص العناصر المحددة من النهاية

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) function

يقص حروف المسافات البيضاء من نهاية نطاق الأحرف.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | نطاق الأحرف الذي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص المسافات البيضاء من النهاية

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) function

يقص حروف المسافات البيضاء من نهاية النطاق القابل للتعديل للأحرف.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | النطاق القابل للتعديل للأحرف الذي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص المسافات البيضاء من النهاية

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) function

يقص الحرف المحدد من نهاية نطاق الأحرف.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | نطاق الأحرف الذي سيُقص |
| trimchar | char16_t | الحرف الذي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص الحرف المحدد من النهاية

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) function

يقص الحرف المحدد من نهاية النطاق القابل للتعديل للأحرف.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | النطاق القابل للتعديل للأحرف الذي سيُقص |
| trimchar | char16_t | الحرف الذي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص الحرف المحدد من النهاية

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

يقص الأحرف المحددة من نهاية نطاق الأحرف.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | نطاق الأحرف الذي سيُقص |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | الأحرف التي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص الأحرف المحددة من النهاية

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

يقص الأحرف المحددة من نهاية النطاق القابل للتعديل للأحرف.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | النطاق القابل للتعديل للأحرف الذي سيُقص |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | الأحرف التي سيُقص |

### قيمة الإرجاع

نطاق جديد مع قص الأحرف المحددة من النهاية

## انظر أيضًا

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)