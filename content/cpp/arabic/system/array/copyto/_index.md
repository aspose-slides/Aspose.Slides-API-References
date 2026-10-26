---
title: CopyTo()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: ينسخ جميع عناصر المصفوفة الحالية إلى المصفوفة الوجهة المحددة. تُدرج العناصر في المصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة الوسيط arrayIndex.
type: docs
weight: 118
url: /ar/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) طريقة

ينسخ جميع عناصر المصفوفة الحالية إلى المصفوفة الوجهة المحددة. يتم إدراج العناصر في المصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة الوسيط arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | مصفوفة الوجهة |
| arrayIndex | int | [Index](../../index/) في المصفوفة الوجهة للبدء بإدراج العناصر المنسوخة عند |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const طريقة

ينسخ جميع عناصر المصفوفة الحالية إلى المصفوفة الوجهة المحددة. يتم إدراج العناصر في المصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة الوسيط dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| DstType | نوع العناصر في المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | مصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة الوجهة للبدء بإدراج العناصر المنسوخة عند |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const طريقة

ينسخ جميع عناصر المصفوفة الحالية إلى عرض المصفوفة الوجهة المحدد. يتم إدراج العناصر في عرض المصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة الوسيط dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| DstType | نوع العناصر في عرض المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | عرض المصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في عرض المصفوفة الوجهة للبدء بإدراج العناصر المنسوخة عند |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const طريقة

ينسخ عددًا محددًا من العناصر من المصفوفة الحالية بدءًا من موضع محدد إلى المصفوفة الوجهة المحددة. يتم إدراج العناصر في المصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة الوسيط dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| DstType | نوع العناصر في المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | مصفوفة الوجهة |
| srcIndex | **int64_t** | [Index](../../index/) في المصفوفة المصدر للبدء بنسخ العناصر عند |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة الوجهة للبدء بإدراج العناصر المنسوخة عند |
| count | **int64_t** | عدد العناصر المراد نسخها |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const طريقة

ينسخ عددًا محددًا من العناصر من المصفوفة الحالية بدءًا من موضع محدد إلى عرض المصفوفة الوجهة المحدد. يتم إدراج العناصر في عرض المصفوفة الوجهة بدءًا من الفهرس المحدد بواسطة الوسيط dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| DstType | نوع العناصر في عرض المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | عرض المصفوفة الوجهة |
| srcIndex | **int64_t** | [Index](../../index/) في المصفوفة المصدر للبدء بنسخ العناصر عند |
| dstIndex | **int64_t** | [Index](../../index/) في عرض المصفوفة الوجهة للبدء بإدراج العناصر المنسوخة عند |
| count | **int64_t** | عدد العناصر المراد نسخها |

## انظر أيضا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [Array](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)