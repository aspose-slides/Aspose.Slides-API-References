---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف ترميزات WebVTT المغلقة إلى نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) طريقة

يضيف الترميزات المغلقة WebVTT إلى نهاية المجموعة.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | تسمية الترميزات المغلقة. |
| filePath | [System::String](../../../system/string/) | مسار ملف WebVTT. |

### قيمة الإرجاع

الكائن [ICaptions](../../icaptions/) المضاف.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) طريقة

يضيف الترميزات المغلقة WebVTT إلى نهاية المجموعة من تدفق.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | تسمية الترميزات المغلقة. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق الإدخال الذي يحتوي على بيانات بصيغة WebVTT. |

### قيمة الإرجاع

الكائن [ICaptions](../../icaptions/) المضاف.

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ICaptions](../../icaptions/)
* فئة [String](../../../system/string/)
* فئة [CaptionsCollection](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)