---
title: Read()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بقراءة العدد المحدد من البايتات من الدفق وكتابتها في مصفوفة البايت المحددة.
type: docs
weight: 196
url: /ar/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يقرأ العدد المحدد من البايتات من الدفق ويكتبها في مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت حيث ستُكتب البايتات المقروءة. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم قراءتها. |

### قيمة الإرجاع

عدد البايتات المقروءة.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يقرأ العدد المحدد من البايتات من الدفق ويكتبها في مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة البايت لكتابة البايتات المقروءة إليه |
| offset | **int32_t** | موضع يبدأ من 0 في **buffer** للبدء بالكتابة |
| size | **int32_t** | عدد البايتات التي سيتم قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [NetworkStream](../)
* مساحة الاسم [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)