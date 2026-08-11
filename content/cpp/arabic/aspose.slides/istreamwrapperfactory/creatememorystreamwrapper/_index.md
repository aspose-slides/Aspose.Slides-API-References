---
title: CreateMemoryStreamWrapper()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: ينشئ غلاف MemoryStream.
type: docs
weight: 1
url: /ar/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() طريقة

ينشئ غلاف MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### قيمة الإرجاع

غلاف الدفق لواجهة COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) طريقة

ينشئ غلاف MemoryStream بناءً على مصفوفة البايت المحددة.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت **uint8_t**[] |

### قيمة الإرجاع

غلاف الدفق لواجهة COM [IStreamWrapper](../../istreamwrapper/)

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IStreamWrapper](../../istreamwrapper/)
* فئة [IStreamWrapperFactory](../)
* نطاق اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)