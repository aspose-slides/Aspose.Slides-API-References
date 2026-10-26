---
title: AddVideo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف نسخة من ملف فيديو من عرض تقديمي آخر.
type: docs
weight: 14
url: /ar/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) طريقة

يضيف نسخة من ملف فيديو من عرض تقديمي آخر.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | فيديو المصدر. |

### قيمة الإرجاع

تمت إضافة الفيديو.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) طريقة

ينشئ فيديوً ويضيفه إلى عرض تقديمي من الدفق.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | الدفق لإضافة ملف الفيديو منه. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | السلوك الذي سيُطبق على الدفق. |

### قيمة الإرجاع

تمت إضافة [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) طريقة

ينشئ فيديوً ويضيفه إلى عرض تقديمي من مصفوفة بايت.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) بايت. |

### قيمة الإرجاع

تمت إضافة الفيديو.

## انظر أيضا

* تعداد [LoadingStreamBehavior](../../loadingstreambehavior/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IVideo](../../ivideo/)
* فئة [IVideoCollection](../)
* فئة [Stream](../../../system.io/stream/)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)