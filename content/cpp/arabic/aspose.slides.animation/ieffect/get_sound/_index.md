---
title: get_Sound()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تم تعريف صوت مدمج للتأثير. اقرأ IAudio.
type: docs
weight: 170
url: /ar/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() طريقة

تم تعريف الصوت المدمج للتأثير. اقرأ [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// يحصل على تسلسل التأثيرات للشرائح
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // يستخرج صوت التأثير في مصفوفة بايت
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAudio](../../../aspose.slides/iaudio/)
* فئة [IEffect](../)
* فضاء أسماء [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)