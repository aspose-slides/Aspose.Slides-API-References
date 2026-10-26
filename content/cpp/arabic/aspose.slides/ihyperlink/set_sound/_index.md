---
title: set_Sound()
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل الصوت المشغل للارتباط التشعبي. اكتب IAudio.
type: docs
weight: 196
url: /ar/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) طريقة

يمثل الصوت المشغل للارتباط التشعبي. اكتب [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على الارتباط التشعبي للشكل الأول
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // استخراج صوت الارتباط التشعبي في مصفوفة بايت
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAudio](../../iaudio/)
* فئة [IHyperlink](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)