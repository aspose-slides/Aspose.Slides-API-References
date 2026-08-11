---
title: Read()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بقراءة عدد البايتات المحدد من التيار ويكتبها إلى مصفوفة البايت المحددة.
type: docs
weight: 27
url: /ar/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

تقرأ عدد البايتات المحدد من التيار وتكتبها إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع 0--اساسي داخل **buffer** لبدء الكتابة عنده |
| count | **int32_t** | عدد البايتات التي يجب قرائتها |

### قيمة الإرجاع

عدد البايتات التي تم قراءتها

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

تقرأ عدد البايتات المحدد من التيار وتكتبها إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع 0--اساسي داخل **buffer** لبدء الكتابة عنده |
| count | **int32_t** | عدد البايتات التي يجب قرائتها |

### قيمة الإرجاع

عدد البايتات التي تم قراءتها

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) طريقة

تقرأ عدد البايتات المحدد من التيار وتكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| N | حجم مصفوفة المكدس |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت المكدسة التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع 0--اساسي داخل **buffer** لبدء الكتابة عنده |
| count | **int32_t** | عدد البايتات التي يجب قراءتها |

### قيمة الإرجاع

عدد البايتات التي تم قراءتها

## Stream::Read(const System::Span\<uint8_t\>\&) طريقة

تقرأ عدد البايتات المحدد من التيار وتكتبها إلى نطاق البايت المحدد.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | نطاق البايت الذي تُكتب فيه البايتات المقروءة |

### قيمة الإرجاع

عدد البايتات التي تم قراءتها

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Stream](../)
* فئة [Span](../../../system/span/)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)