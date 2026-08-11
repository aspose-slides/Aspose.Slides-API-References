---
title: set_RepeatUntilEndSlide()
second_title: مرجع API Aspose.Slides برای C++
description: این ویژگی مشخص می‌کند که آیا اثر تا پایان اسلاید تکرار شود یا نه. مقدار bool را بنویسید.
type: docs
weight: 144
url: /fa/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) متد


این ویژگی مشخص می‌کند که آیا افکت تا پایان اسلاید تکرار شود یا نه. مقدار **bool** را بنویسید.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## موارد مرتبط

* کلاس [Timing](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)