---
title: get_Sound()
second_title: مرجع API Aspose.Slides لـ C++
description: يمثل الصوت المشغل للارتباط التشعبي. اقرأ IAudio.
type: docs
weight: 183
url: /ar/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() طريقة

يمثل الصوت المشغل للارتباط التشعبي. اقرأ [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على الارتباط التشعبي لأول شكل
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // استخراج صوت الارتباط التشعبي كمصفوفة بايت
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAudio](../../iaudio/)
* فئة [IHyperlink](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)