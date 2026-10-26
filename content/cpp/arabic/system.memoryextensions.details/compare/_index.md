---
title: Compare()
second_title: مرجع API Aspose.Slides للغة C++
description: يقارن مؤشرين ذكيين.
type: docs
weight: 1
url: /ar/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) دالة

يقارن مؤشرين ذكيين.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المؤشر الذكي الأول |
| U | نوع المؤشر الذكي الثاني |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | المؤشر الذكي الأول |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | المؤشر الذكي الثاني |

### قيمة الإرجاع

[Comparison](../../system/comparison/) النتيجة (0 إذا كان متساويًا، -1 إذا a < b، 1 إذا a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) دالة

يقارن قيمتين عدديتين.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع حسابي |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | const T\& | القيمة الأولى |
| b | const T\& | القيمة الثانية |

### قيمة الإرجاع

[Comparison](../../system/comparison/) النتيجة (0 إذا كان متساويًا، -1 إذا a < b، 1 إذا a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) دالة

يقارن مؤشرًا ذكيًا مع قيمة.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع الذي يشيره المؤشر الذكي |
| U | نوع القيمة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | المؤشر الذكي |
| b | const U\& | القيمة |

### قيمة الإرجاع

[Comparison](../../system/comparison/) النتيجة (0 إذا كان متساويًا، -1 إذا a < b، 1 إذا a > b)

## انظر أيضًا

* تعريف نوع [SharedPtr](../../system/sharedptr/)
* النطاق [System::MemoryExtensions::Details](../)
* مكتبة [Aspose.Slides](../../)