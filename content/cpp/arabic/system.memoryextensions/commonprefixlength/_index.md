---
title: CommonPrefixLength()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد طول البادئة المشتركة بين نطاقين.
type: docs
weight: 27
url: /ar/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

يحدد طول البادئة المشتركة بين نطاقين.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الأول |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الثاني |

### قيمة الإرجاع

عدد العناصر المتطابقة في بداية كلا النطاقين

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

يحدد طول البادئة المشتركة بين نطاق قابل للتعديل ونطاق للقراءة فقط.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للقراءة فقط |

### قيمة الإرجاع

عدد العناصر المتطابقة في بداية كلا النطاقين

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) function

يحدد طول البادئة المشتركة بين نطاقين قابلين للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الأول |
| other | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الثاني |

### قيمة الإرجاع

عدد العناصر المتطابقة في بداية كلا النطاقين

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

يحدد طول البادئة المشتركة بين نطاقين باستخدام مُقارن مساواة مخصص.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |
| TEqualityComparer | نوع مُقارن المساواة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الأول |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الثاني |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | مُقارن المساواة المستخدم للمقارنة بين العناصر |

### قيمة الإرجاع

عدد العناصر المتطابقة في بداية كلا النطاقين

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

يحدد طول البادئة المشتركة بين نطاق قابل للتعديل ونطاق للقراءة فقط باستخدام مُقارن مساواة مخصص.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |
| TEqualityComparer | نوع مُقارن المساواة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للقراءة فقط |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | مُقارن المساواة المستخدم للمقارنة بين العناصر |

### قيمة الإرجاع

عدد العناصر المتطابقة في بداية كلا النطاقين

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

يحدد طول البادئة المشتركة بين نطاقين قابلين للتعديل باستخدام مُقارن مساواة مخصص.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |
| TEqualityComparer | نوع مُقارن المساواة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الأول |
| other | const [Span](../../system/span/)\<T\>\& | النطاق القابل للتعديل الثاني |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | مُقارن المساواة المستخدم للمقارنة بين العناصر |

### قيمة الإرجاع

عدد العناصر المتطابقة في بداية كلا النطاقين

## انظر أيضًا

* تعريف نوع [SharedPtr](../../system/sharedptr/)
* الصنف [ReadOnlySpan](../../system/readonlyspan/)
* الصنف [Span](../../system/span/)
* المساحة الاسمية [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)