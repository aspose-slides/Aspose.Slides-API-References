---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides برای C++ مرجع API
description: این ویژگی مشخص می‌کند که آیا اثر تا انتهای اسلاید تکرار می‌شود. مقدار bool نوشته می‌شود.
type: docs
weight: 144
url: /fa/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) متد

این ویژگی مشخص می‌کند که آیا اثر تا پایان اسلاید تکرار می‌شود. مقدار **bool** نوشته می‌شود.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
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

## مطالب مرتبط

* کلاس [ITiming](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)