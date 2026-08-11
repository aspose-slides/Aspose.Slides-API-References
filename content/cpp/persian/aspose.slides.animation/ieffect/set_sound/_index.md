---
title: set_Sound()
second_title: مرجع API Aspose.Slides برای C++
description: صداهای توکار برای افکت تعریف شد. IAudio را بنویسید.
type: docs
weight: 183
url: /fa/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) متد

صداهای توکار برای افکت تعریف شد. [IAudio](../../../aspose.slides/iaudio/) را بنویسید.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// دنبالهٔ افکت‌ها را برای اسلاید دریافت می‌کند
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // صدای افکت را به صورت آرایه بایت استخراج می‌کند
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## مراجعه

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../../aspose.slides/iaudio/)
* کلاس [IEffect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)