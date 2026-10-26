---
title: get_DelayBetweenTextParts()
second_title: مرجع API Aspose.Slides برای C++
description: تعریف یک تاخیر بین بخش‌های متنی انیمیشن‌شده (کلمات یا حروف). یک مقدار مثبت درصد مدت اثر را مشخص می‌کند. یک مقدار منفی تاخیر را بر حسب ثانیه تعیین می‌کند. خواندن float.
type: docs
weight: 300
url: /fa/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() متد

یک تاخیر بین بخش‌های متنی انیمیشن‌شده (کلمات یا حروف) تعریف می‌کند. یک مقدار مثبت درصد مدت اثر را مشخص می‌کند. یک مقدار منفی تاخیر را بر حسب ثانیه مشخص می‌کند. خواندن **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## توضیات

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