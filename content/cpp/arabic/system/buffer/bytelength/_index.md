---
title: ByteLength()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد عدد البايتات التي يشغلها جميع عناصر المصفوفة المحددة.
type: docs
weight: 14
url: /ar/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) طريقة

يحدد عدد البايتات التي يشغلها جميع عناصر المصفوفة المحددة.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع عناصر المصفوفة |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | مصفوفة |

### قيمة الإرجاع

عدد البايتات التي يشغلها جميع عناصر المصفوفة المحددة

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) طريقة

يحدد عدد البايتات التي يشغلها جميع عناصر المصفوفة المحددة.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع عناصر عرض المصفوفة |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | عرض مصفوفة |

### قيمة الإرجاع

عدد البايتات التي يشغلها جميع عناصر عرض المصفوفة المحددة

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) طريقة


يحدد عدد البايتات التي يشغلها جميع عناصر المصفوفة المحددة.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T | نوع عناصر مصفوفة المكدس |
| N | حجم مصفوفة المكدس |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | مصفوفة مكدس |

### قيمة الإرجاع

عدد البايتات التي يش Occupy جميع عناصر مصفوفة المكدس المحددة

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Array](../../array/)
* فئة [Buffer](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)