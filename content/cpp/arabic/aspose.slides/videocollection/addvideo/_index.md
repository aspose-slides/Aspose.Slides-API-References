---
title: AddVideo()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضيف نسخة من ملف فيديو من عرض تقديمي آخر.
type: docs
weight: 53
url: /ar/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) طريقة

يضيف نسخة من ملف فيديو من عرض تقديمي آخر.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | فيديو المصدر. |

### قيمة الإرجاع

الفيديو المضاف.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) طريقة

ينشئ ويضيف فيديو إلى عرض تقديمي من التدفق.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق لإضافة ملف الفيديو منه. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | السلوك الذي سيُطبّق على التدفق. |

### قيمة الإرجاع

تمت إضافة [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) طريقة

ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) بايت. |

### قيمة الإرجاع

الفيديو المضاف.

## انظر أيضًا

* تعداد [LoadingStreamBehavior](../../loadingstreambehavior/)
* التعريف [SharedPtr](../../../system/sharedptr/)
* التعريف [ArrayPtr](../../../system/arrayptr/)
* فئة [IVideo](../../ivideo/)
* فئة [VideoCollection](../)
* فئة [Stream](../../../system.io/stream/)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)