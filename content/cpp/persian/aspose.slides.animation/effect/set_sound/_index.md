---
title: set_Sound()
second_title: Aspose.Slides برای C++ مرجع API
description: صدای توکار برای افکت تعریف می‌شود. IAudio را بنویسید.
type: docs
weight: 183
url: /fa/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) متد


صدای توکار برای افکت تعریف می‌شود. [IAudio](../../../aspose.slides/iaudio/) را بنویسید.

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// دریافت توالی افکت‌ها برای اسلاید
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




## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../../aspose.slides/iaudio/)
* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)