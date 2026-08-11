---
title: Read()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا كان وضع التغليف ثنائيًا، يقرأ العدد المحدد من البايتات من التدفق، وإلا يقرأ العدد المحدد من الأحرف ويحولها إلى النوع uint8_t. يكتب نتيجة القراءة إلى مصفوفة البايت المحددة.
type: docs
weight: 66
url: /ar/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

إذا كان وضع التغليف ثنائيًا، يقرأ العدد المحدد من البايتات من التدفق، وإلا يقرأ العدد المحدد من الأحرف ويحولها إلى النوع **uint8_t**. يكتب نتيجة القراءة إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت لكتابة البايتات المقروءة إليها |
| offset | **int32_t** | موضع يبدأ من 0 في **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات التي سيتم قراءتها |

### قيمة الإرجاع

عدد البايتات أو الأحرف المقروءة

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

يقرأ العدد المحدد من البايتات من التدفق ويكتبها إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة البايت لكتابة البايتات المقروءة إليها |
| offset | **int32_t** | موضع يبدأ من 0 في **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات التي سيتم قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## راجع أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)