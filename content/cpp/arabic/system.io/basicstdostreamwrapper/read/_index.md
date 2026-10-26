---
title: Read()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: إذا كان وضع التغليف ثنائيًا، يقرأ العدد المحدد من البايتات من الدفق، وإلا يقرأ العدد المحدد من الأحرف ويحولها إلى النوع uint8_t. يكتب نتيجة القراءة إلى مصفوفة البايت المحددة. غير مدعوم!
type: docs
weight: 66
url: /ar/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

إذا كان وضع التغليف ثنائيًا، يقرأ العدد المحدد من البايتات من الدفق، وإلا يقرأ العدد المحدد من الأحرف ويحوله إلى النوع **uint8_t**. يكتب نتيجة القراءة إلى مصفوفة البايت المحددة. غير مدعوم!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت لكتابة البايتات المقروءة إليها |
| offset | **int32_t** | موضع يبدأ من صفر داخل **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات التي سيتم قرأتها |

### Return Value

عدد البايتات أو الأحرف المقروءة

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يقرأ العدد المحدد من البايتات من الدفق ويكتبها إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | مصفوفة عرض البايت لكتابة البايتات المقروءة إليها |
| offset | **int32_t** | موضع يبدأ من صفر داخل **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات التي سيتم قرأتها |

### Return Value

عدد البايتات المقروءة

## أنظر أيضا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [BasicSTDOStreamWrapper](../)
* مساحة أسماء [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)