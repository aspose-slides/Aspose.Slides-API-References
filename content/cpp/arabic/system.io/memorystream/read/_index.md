---
title: Read()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بقراءة العدد المحدد من البايتات من الدفق وكتابتها إلى مصفوفة البايت المحددة.
type: docs
weight: 79
url: /ar/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة


يقرأ العدد المحدد من البايتات من الدفق ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت لكتابة البايتات المقروءة إليها |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات التي يجب قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة


يقرأ العدد المحدد من البايتات من الدفق ويكتبها إلى عرض مصفوفة البايت المحدد.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة البايت لكتابة البايتات المقروءة إليه |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات التي يجب قراؤها |

### قيمة الإرجاع

عدد البايتات المقروءة

## أنظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [MemoryStream](../)
* نطاق [System::IO](../../)
* Library [Aspose.Slides](../../../)