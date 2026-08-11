---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides برای مرجع API C++
description: این ویژگی تعیین می‌کند آیا اثر تا کلیک بعدی تکرار می‌شود. مقدار bool را بنویسید.
type: docs
weight: 170
url: /fa/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) متد


این ویژگی تعیین می‌کند آیا اثر تا کلیک بعدی تکرار می‌شود یا نه. مقدار **bool** را بنویسید.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
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

## مراجع

* کلاس [ITiming](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)