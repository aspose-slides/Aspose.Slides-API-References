---
title: get_Sound()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تم تعريف صوت مدمج للتأثير. اقرأ IAudio.
type: docs
weight: 170
url: /ar/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() طريقة


تم تعريف صوت مدمج للتأثير. اقرأ [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// يجلب تسلسل التأثيرات للشريحة
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // يستخرج صوت التأثير كمصفوفة بايت
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAudio](../../../aspose.slides/iaudio/)
* فئة [Effect](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)