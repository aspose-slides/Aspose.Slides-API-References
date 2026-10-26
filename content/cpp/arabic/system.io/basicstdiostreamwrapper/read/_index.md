---
title: Read()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا كان وضع الالتفاف ثنائيًا، يقرأ العدد المحدد من البايتات من الدفق، وإلا يقرأ العدد المحدد من الأحرف ويحولها إلى النوع uint8_t. يكتب نتيجة القراءة إلى مصفوفة البايت المحددة.
type: docs
weight: 66
url: /ar/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة


إذا كان وضع الالتفاف ثنائيًا، يقرأ العدد المحدد من البايتات من الدفق، وإلا يقرأ العدد المحدد من الأحرف ويحولها إلى النوع **uint8_t**. يكتب نتيجة القراءة إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** لبدء الكتابة |
| count | **int32_t** | عدد البايتات المراد قراءتها |

### قيمة الإرجاع

عدد البايتات أو الأحرف المقروءة

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة


يقوم بقراءة العدد المحدد من البايتات من الدفق ويكتبها إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** لبدء الكتابة |
| count | **int32_t** | عدد البايتات المراد قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [BasicSTDIOStreamWrapper](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)