---
title: Copy()
second_title: مرجع API ل Aspose.Slides للغة C++
description: ينسخ العدد المحدد من العناصر من المصفوفة المصدر إلى المصفوفة الوجهة.
type: docs
weight: 729
url: /ar/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

ينسخ العدد المحدد من العناصر من المصفوفة المصدر إلى المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | المصفوفة المصدر |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | المصفوفة الوجهة |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method

ينسخ العدد المحدد من العناصر من عرض المصفوفة المصدر إلى المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | عرض المصفوفة المصدر |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | المصفوفة الوجهة |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method

ينسخ العدد المحدد من العناصر من المصفوفة المصدر إلى عرض المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | المصفوفة المصدر |
| dstArray | System::Details::ArrayView\<DstType\> | عرض المصفوفة الوجهة |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method

ينسخ العدد المحدد من العناصر من عرض المصفوفة المصدر إلى عرض المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | عرض المصفوفة المصدر |
| dstArray | System::Details::ArrayView\<DstType\> | عرض المصفوفة الوجهة |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

ينسخ العدد المحدد من العناصر من المصفوفة على الذاكرة المؤقتة إلى المصفوفة الوجهة.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | المصفوفة على الذاكرة المؤقتة |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | المصفوفة الوجهة |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method

ينسخ العدد المحدد من العناصر من المصفوفة المصدر إلى المصفوفة على الذاكرة المؤقتة.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | المصفوفة المصدر |
| dstArray | System::Details::StackArray\<DstType, N\>\& | المصفوفة على الذاكرة المؤقتة |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method

ينسخ العدد المحدد من العناصر من المصفوفة على الذاكرة المؤقتة إلى المصفوفة على الذاكرة المؤقتة.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | المصفوفة على الذاكرة المؤقتة |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | المصفوفة على الذاكرة المؤقتة |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من المصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في المصفوفة المصدر |
| DstType | نوع العناصر في المصفوفة الوجهة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | المصفوفة المصدر |
| srcIndex | **int64_t** | [Index](../../index/) في المصفوفة المصدر الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | المصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة الوجهة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من عرض المصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في عرض المصفوفة المصدر |
| DstType | نوع العناصر في المصفوفة الوجهة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | عرض المصفوفة المصدر |
| srcIndex | **int64_t** | [Index](../../index/) في عرض المصفوفة المصدر الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | المصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة الوجهة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من المصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في عرض المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في المصفوفة المصدر |
| DstType | نوع العناصر في عرض المصفوفة الوجهة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | المصفوفة المصدر |
| srcIndex | **int64_t** | [Index](../../index/) في المصفوفة المصدر الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | System::Details::ArrayView\<DstType\> | عرض المصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في عرض المصفوفة الوجهة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من عرض المصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في عرض المصفوفة الوجهة.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في عرض المصفوفة المصدر |
| DstType | نوع العناصر في عرض المصفوفة الوجهة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | عرض المصفوفة المصدر |
| srcIndex | **int64_t** | [Index](../../index/) في عرض المصفوفة المصدر الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | System::Details::ArrayView\<DstType\> | عرض المصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في عرض المصفوفة الوجهة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من المصفوفة على الذاكرة المؤقتة بدءًا من الفهرس المحدد إلى الموضع المحدد في المصفوفة الوجهة.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في المصفوفة على الذاكرة المؤقتة |
| DstType | نوع العناصر في المصفوفة الوجهة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | المصفوفة على الذاكرة المؤقتة |
| srcIndex | **int64_t** | [Index](../../index/) في المصفوفة على الذاكرة المؤقتة الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | المصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة الوجهة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من المصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في المصفوفة على الذاكرة المؤقتة.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في المصفوفة المصدر |
| DstType | نوع العناصر في المصفوفة على الذاكرة المؤقتة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | المصفوفة المصدر |
| srcIndex | **int64_t** | [Index](../../index/) في المصفوفة المصدر الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | System::Details::StackArray\<DstType, N\>\& | المصفوفة على الذاكرة المؤقتة |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة على الذاكرة المؤقتة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من المصفوفة على الذاكرة المؤقتة بدءًا من الفهرس المحدد إلى الموضع المحدد في المصفوفة على الذاكرة المؤقتة.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في المصفوفة على الذاكرة المؤقتة |
| DstType | نوع العناصر في المصفوفة على الذاكرة المؤقتة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | المصفوفة على الذاكرة المؤقتة |
| srcIndex | **int64_t** | [Index](../../index/) في المصفوفة على الذاكرة المؤقتة الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | المصفوفة على الذاكرة المؤقتة |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة على الذاكرة المؤقتة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

ينسخ عددًا محددًا من العناصر من عرض المصفوفة المصدر بدءًا من الفهرس المحدد إلى الموضع المحدد في المصفوفة على الذاكرة المؤقتة.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في المصفوفة على الذاكرة المؤقتة |
| DstType | نوع العناصر في المصفوفة على الذاكرة المؤقتة |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | عرض المصفوفة المصدر |
| srcIndex | **int64_t** | [Index](../../index/) في عرض المصفوفة المصدر الذي يحدد بداية نطاق العناصر التي ستُنسخ |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | المصفوفة على الذاكرة المؤقتة |
| dstIndex | **int64_t** | [Index](../../index/) في المصفوفة على الذاكرة المؤقتة لبدء إدراج العناصر المنسوخة عنده |
| count | **int64_t** | عدد العناصر التي سيتم نسخها |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)