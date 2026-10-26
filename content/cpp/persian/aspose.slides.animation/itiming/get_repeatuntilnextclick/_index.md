---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides برای مرجع API C++
description: این ویژگی مشخص می‌کند که آیا اثر تا کلیک بعدی تکرار می‌شود. خواندن bool.
type: docs
weight: 157
url: /fa/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() متد

این ویژگی مشخص می‌کند که آیا اثر تا کلیک بعدی تکرار می‌شود. خواندن **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// دنبالهٔ افکت‌ها را برای اولین اسلاید دریافت می‌کند
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// اولین افکت دنبالهٔ اصلی را دریافت می‌کند.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// تغییر زمان/تکرار افکت به "تا انتهای اسلاید"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## مراجع

* کلاس [ITiming](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)