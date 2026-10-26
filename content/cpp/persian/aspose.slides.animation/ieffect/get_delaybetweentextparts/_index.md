---
title: get_DelayBetweenTextParts()
second_title: مرجع API Aspose.Slides برای C++
description: یک تأخیر بین بخش‌های متنی انیمیشن‌شده (کلمات یا حروف) تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تأخیر را بر حسب ثانیه مشخص می‌کند. خواندن float.
type: docs
weight: 300
url: /fa/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() متد

یک تأخیر بین بخش‌های متنی انیمیشن‌شده (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تأخیر را بر حسب ثانیه مشخص می‌کند. خواندن **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## موارد مرتبط

* کلاس [IEffect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)