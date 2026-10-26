---
title: set_DelayBetweenTextParts()
second_title: مرجع API Aspose.Slides برای C++
description: تاخیر بین بخش‌های متنی انیمیشن‌شده (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت‌زمان اثر را مشخص می‌کند. مقدار منفی تاخیر را به ثانیه تعیین می‌کند. مقدار float را بنویسید.
type: docs
weight: 313
url: /fa/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) متد


تاخیر بین بخش‌های متنی انیمیشن‌شده (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت‌زمان اثر را مشخص می‌کند. مقدار منفی تاخیر را به ثانیه تعیین می‌کند. مقدار **float** را بنویسید.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## مراجع

* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)