---
title: get_Sound()
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل الصوت المشغل للرابط التشعبي. اقرأ IAudio.
type: docs
weight: 287
url: /ar/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() طريقة


يمثل الصوت المشغل للرابط التشعبي. اقرأ [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// الحصول على الارتباط التشعبي لأول شكل
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // استخراج صوت الارتباط التشعبي في مصفوفة بايت
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAudio](../../iaudio/)
* فئة [Hyperlink](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)