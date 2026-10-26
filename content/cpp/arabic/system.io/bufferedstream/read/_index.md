---
title: Read()
second_title: مرجع API Aspose.Slides for C++
description: يقرأ عدد البايتات المحدد من الدفق الأساسي ويكتبها إلى مصفوفة البايتات المحددة.
type: docs
weight: 53
url: /ar/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يقوم بقراءة عدد البايتات المحدد من الدفق الأساسي ويكتبها إلى مصفوفة البايتات المحددة.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب إليها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** لبدء الكتابة |
| count | **int32_t** | عدد البايتات التي يجب قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يقوم بقراءة عدد البايتات المحدد من الدفق الأساسي ويكتبها إلى مصفوفة البايتات المحددة.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب إليها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** لبدء الكتابة |
| count | **int32_t** | عدد البايتات التي يجب قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [BufferedStream](../)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)