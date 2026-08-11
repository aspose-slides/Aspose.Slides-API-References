---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides برای مرجع API C++
description: این ویژگی مشخص می‌کند که آیا اثر تا کلیک بعدی تکرار خواهد شد. خوانده می‌شود bool.
type: docs
weight: 157
url: /fa/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() متد


این ویژگی مشخص می‌کند که آیا اثر تا کلیک بعدی تکرار خواهد شد. خوانده می‌شود **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## موارد مرتبط

* کلاس [Timing](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)