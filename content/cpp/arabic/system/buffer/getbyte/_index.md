---
title: GetByte()
second_title: مرجع API Aspose.Slides للـ C++
description: يفسر المصفوفة ذات النوع المحدد كمصفوفة بايتات خام ويسترجع قيمة البايت عند الإزاحة المحددة بالبايت.
type: docs
weight: 27
url: /ar/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) طريقة

يفسر المصفوفة ذات النوع المحدد كمصفوفة بايتات خام ويسترجع قيمة البايت عند الإزاحة المحددة بالبايت.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المصفوفة |

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | المصفوفة الهدف |
| index | int | الإزاحة الصفرية للبايت المراد استرجاعه |

### قيمة الإرجاع

قيمة البايت عند الفهرس المحدد

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) طريقة

يفسر عرض المصفوفة ذات النوع المحدد كمصفوفة بايتات خام ويسترجع قيمة البايت عند الإزاحة المحددة بالبايت.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر عرض المصفوفة |

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | عرض المصفوفة الهدف |
| index | int | الإزاحة الصفرية للبايت المراد استرجاعه |

### قيمة الإرجاع

قيمة البايت عند الفهرس المحدد

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) طريقة

يفسر مصفوفة المكدس ذات النوع المحدد كمصفوفة بايتات خام ويسترجع قيمة البايت عند الإزاحة المحددة بالبايت.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر مصفوفة المكدس |
| N | حجم مصفوفة المكدس |

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | مصفوفة المكدس الهدف |
| index | int | الإزاحة الصفرية للبايت المراد استرجاعه |

### قيمة الإرجاع

قيمة البايت عند الفهرس المحدد

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)