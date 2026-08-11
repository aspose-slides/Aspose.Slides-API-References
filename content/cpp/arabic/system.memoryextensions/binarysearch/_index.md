---
title: BinarySearch()
second_title: مرجع API Aspose.Slides للغة C++
description: يُجري بحثًا ثنائيًا على مدى مُرتب.
type: docs
weight: 14
url: /ar/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) دالة


يقوم بإجراء بحث ثنائي على مدى مُرتب.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |
| TComparable | نوع القيمة القابلة للمقارنة |

### المتغيرات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى المرتب للبحث فيه |
| comparable | const TComparable\& | القيمة المطلوب البحث عنها |

### قيمة الإرجاع

[Index](../../system/index/) للعنصر الموجود، أو مكمل ثنائي للموضع الإدراجي إذا لم يُعثر عليه

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) دالة


يقوم بإجراء بحث ثنائي على مدى مُرتب باستخدام مُقارن مخصص.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |
| TComparer | نوع المُقارن |

### المتغيرات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى المرتب للبحث فيه |
| value | const T\& | القيمة المطلوب البحث عنها |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | المُقارن المُستَخدم للمقارنات |

### قيمة الإرجاع

[Index](../../system/index/) للعنصر الموجود، أو مكمل ثنائي للموضع الإدراجي إذا لم يُعثر عليه

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) دالة


يقوم بإجراء بحث ثنائي على مدى مُرتب قابل للتغيير.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |
| TComparable | نوع القيمة القابلة للمقارنة |

### المتغيرات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى المرتب للبحث فيه |
| comparable | const TComparable\& | القيمة المطلوب البحث عنها |

### قيمة الإرجاع

[Index](../../system/index/) للعنصر الموجود، أو مكمل ثنائي للموضع الإدراجي إذا لم يُعثر عليه

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) دالة


يقوم بإجراء بحث ثنائي على مدى مُرتب قابل للتغيير باستخدام مُقارن مخصص.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |
| TComparer | نوع المُقارن |

### المتغيرات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى المرتب للبحث فيه |
| value | const T\& | القيمة المطلوب البحث عنها |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | المُقارن المُستَخدم للمقارنات |

### قيمة الإرجاع

[Index](../../system/index/) للعنصر الموجود، أو مكمل ثنائي للموضع الإدراجي إذا لم يُعثر عليه

## انظر أيضاً

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)