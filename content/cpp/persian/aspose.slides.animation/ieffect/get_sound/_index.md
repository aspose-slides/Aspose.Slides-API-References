---
title: get_Sound()
second_title: مرجع API Aspose.Slides برای C++
description: صدای توکار برای اثر تعریف می‌شود. IAudio را بخوانید.
type: docs
weight: 170
url: /fa/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() متد

صدای توکار برای افکت تعریف می‌شود. [IAudio](../../../aspose.slides/iaudio/) را بخوانید.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// دریافت دنباله اثرها برای اسلاید
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // استخراج صدای افکت به صورت آرایه بایت
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## مراجع

* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../../aspose.slides/iaudio/)
* کلاس [IEffect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)