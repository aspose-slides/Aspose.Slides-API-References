---
title: Contains()
second_title: مرجع API Aspose.Slides للغة C++
description: يتحقق مما إذا كان نطاق للقراءة فقط يحتوي على قيمة محددة.
type: docs
weight: 40
url: /ar/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) function

يتحقق مما إذا كان نطاق للقراءة فقط يحتوي على قيمة محددة.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value | const T\& | القيمة المراد البحث عنها |

### قيمة الإرجاع

true إذا تم العثور على القيمة في النطاق، false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) function

يتحقق مما إذا كان نطاقًا قابلًا للتغيير يحتوي على قيمة محددة.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتغيير للبحث فيه |
| value | const T\& | القيمة المراد البحث عنها |

### قيمة الإرجاع

true إذا تم العثور على القيمة في النطاق، false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

يتحقق مما إذا كان نطاق الأحرف يحتوي على نطاق أحرف آخر وفقًا لقواعد المقارنة المحددة.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | النطاق للبحث فيه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | النطاق المراد البحث عنه |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقارنة السلاسل التي يجب إجراؤها |

### قيمة الإرجاع

true إذا تم العثور على القيمة في النطاق، false otherwise

## انظر أيضًا

* Enum [StringComparison](../../system/stringcomparison/)
* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)