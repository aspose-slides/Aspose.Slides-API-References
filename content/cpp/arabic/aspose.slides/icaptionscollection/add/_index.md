---
title: Add()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف تسميات توضيحية مغلقة بتنسيق WebVTT إلى نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) طريقة

يضيف تسميات توضيحية مغلقة بتنسيق WebVTT إلى نهاية المجموعة.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | التسمية التوضيحية للتسميات المغلقة. |
| filePath | [System::String](../../../system/string/) | المسار إلى ملف WebVTT. |

### قيمة الإرجاع

مثيل [ICaptions](../../icaptions/) المضاف.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) طريقة

يضيف تسميات توضيحية مغلقة بتنسيق WebVTT إلى نهاية المجموعة من تدفق.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | التسمية التوضيحية للتسميات المغلقة. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق الإدخال الذي يحتوي على بيانات بتنسيق WebVTT. |

### قيمة الإرجاع

مثيل [ICaptions](../../icaptions/) المضاف.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ICaptions](../../icaptions/)
* فئة [String](../../../system/string/)
* فئة [ICaptionsCollection](../)
* فئة [Stream](../../../system.io/stream/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)