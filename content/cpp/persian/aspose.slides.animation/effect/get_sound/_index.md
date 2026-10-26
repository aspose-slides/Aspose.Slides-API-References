---
title: get_Sound()
second_title: Aspose.Slides برای مرجع API C++
description: صوت تعبیه‌شده برای اثر تعریف شد. IAudio را بخوانید.
type: docs
weight: 170
url: /fa/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() متد

صوت تعبیه‌شده برای اثر تعریف شد. بخوانید [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// دنباله افکت‌های اسلاید را دریافت می‌کند
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // صدا اثر را به صورت آرایه بایتی استخراج می‌کند
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## مراجع

* نوع تعریف‌شده [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../../aspose.slides/iaudio/)
* کلاس [Effect](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)