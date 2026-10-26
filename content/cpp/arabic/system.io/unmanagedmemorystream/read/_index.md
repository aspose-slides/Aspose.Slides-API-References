---
title: Read()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بقراءة عدد البايتات المحدد من الدفق וكتابتها إلى مصفوفة البايت المحددة.
type: docs
weight: 144
url: /ar/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يقوم بقراءة عدد البايتات المحدد من الدفق وكتابتها إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات المراد قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يقوم بقراءة عدد البايتات المحدد من الدفق وكتابتها إلى مصفوفة البايت المحددة.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة |
| count | **int32_t** | عدد البايتات المراد قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## انظر أيضًا

* نوع تعريف [ArrayPtr](../../../system/arrayptr/)
* الفئة [UnmanagedMemoryStream](../)
* نطاق الاسم [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)