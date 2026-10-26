---
title: StartsWith()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يتحقق مما إذا كان المدى يبدأ بالقيمة المحددة.
type: docs
weight: 352
url: /ar/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) دالة

يتحقق مما إذا كان المدى يبدأ بالقيمة المحددة.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى المراد التحقق منه |
| value | const T\& | القيمة التي يتم التحقق منها في بداية المدى |

### قيمة الإرجاع

صحيح إذا كان المدى يبدأ بالقيمة، خطأ خلاف ذلك

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يتحقق مما إذا كان المدى يبدأ بمدى القيمة المحدد.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى المراد التحقق منه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى الذي يحتوي على القيم التي يتم التحقق منها في البداية |

### قيمة الإرجاع

صحيح إذا كان المدى يبدأ بمدى القيمة، خطأ خلاف ذلك

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يتحقق مما إذا كان المدى القابل للتعديل يبدأ بمدى القيمة القراءة فقط المحدد.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى القابل للتعديل المراد التحقق منه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى القراءة فقط الذي يحتوي على القيم التي يتم التحقق منها |

### قيمة الإرجاع

صحيح إذا كان المدى يبدأ بمدى القيمة، خطأ خلاف ذلك

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) دالة

يتحقق مما إذا كان المدى القراءة فقط يبدأ بمدى القيمة القابل للتعديل المحدد.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى القراءة فقط المراد التحقق منه |
| value | const [Span](../../system/span/)\<T\>\& | المدى القابل للتعديل الذي يحتوي على القيم التي يتم التحقق منها |

### قيمة الإرجاع

صحيح إذا كان المدى يبدأ بمدى القيمة، خطأ خلاف ذلك

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) دالة

يتحقق مما إذا كان مدى الأحرف يبدأ بمدى القيمة المحدد باستخدام مقارنة السلاسل.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | مدى الأحرف المراد التحقق منه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | مدى الأحرف الذي يحتوي على القيم التي يتم التحقق منها |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقارنة السلاسل التي يجب إجراؤها |

### قيمة الإرجاع

صحيح إذا كان المدى يبدأ بمدى القيمة، خطأ خلاف ذلك

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) دالة

يتحقق مما إذا كان مدى السلسلة يبدأ بمصفوفة الأحرف المحددة.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | مدى السلسلة المراد التحقق منه |
| val | const char16_t * | مصفوفة الأحرف التي يتم التحقق منها في البداية |

### قيمة الإرجاع

صحيح إذا كان المدى يبدأ بمصفوفة الأحرف، خطأ خلاف ذلك

## انظر أيضًا

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)