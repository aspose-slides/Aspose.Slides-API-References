---
title: Sort()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بترتيب Span باستخدام مقارن مخصص.
type: docs
weight: 339
url: /ar/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) دالة

يقوم بترتيب [Span](../../system/span/) باستخدام مقارن مخصص.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span |
| TComparer | نوع كائن المقارن |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | الـ span للترتيب |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | مؤشر ذكي إلى كائن المقارن لمقارنة العناصر |

## System::MemoryExtensions::Sort(Span\<T\>\&) دالة

يقوم بترتيب [Span](../../system/span/) باستخدام مقارنة افتراضية.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | الـ span للترتيب |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) دالة

يقوم بترتيب أزواج المفتاح والقيمة باستخدام مقارن مخصص (يتم ترتيب المفاتيح والقيم معاً)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |
| TComparer | نوع كائن المقارن |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | الـ span للمفاتيح للترتيب |
| values | [Span](../../system/span/)\<TValue\>\& | الـ span للقيم للترتيب (مع الحفاظ على المطابقة مع المفاتيح) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | مؤشر ذكي إلى كائن المقارن لمقارنة المفاتيح |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) دالة

يقوم بترتيب أزواج المفتاح والقيمة باستخدام مفوض مقارنة.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | الـ span للمفاتيح للترتيب |
| values | [Span](../../system/span/)\<TValue\>\& | الـ span للقيم للترتيب |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) مفوض لمقارنة المفاتيح |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) دالة

يقوم بترتيب أزواج المفتاح والقيمة باستخدام مقارنة افتراضية.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | الـ span للمفاتيح للترتيب |
| values | [Span](../../system/span/)\<TValue\>\& | الـ span للقيم للترتيب |

## انظر أيضاً

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Span](../../system/span/)
* Class [Comparison](../../system/comparison/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)