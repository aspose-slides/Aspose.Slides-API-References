---
title: get_RepeatUntilEndSlide()
second_title: مرجع API Aspose.Slides برای C++
description: این ویژگی مشخص می‌کند که آیا اثر تا پایان اسلاید تکرار شود. خوانده می‌شود bool.
type: docs
weight: 131
url: /fa/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() متد


این ویژگی مشخص می‌کند که آیا اثر تا انتهای اسلاید تکرار شود یا نه. خوانده می‌شود **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// دریافت توالی اثرها برای اولین اسلاید
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// دریافت اولین اثر از توالی اصلی.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// تغییر اثر Timing/Repeat به "تا انتهای اسلاید"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## موارد دیگر

* کلاس [Timing](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)