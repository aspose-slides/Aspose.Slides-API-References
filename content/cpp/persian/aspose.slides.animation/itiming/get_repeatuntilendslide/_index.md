---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides برای C++ مرجع API
description: این ویژگی مشخص می‌کند که آیا اثر تا انتهای اسلاید تکرار می‌شود یا نه. خواندن bool.
type: docs
weight: 131
url: /fa/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() متد

این ویژگی مشخص می‌کند که آیا اثر تا انتهای اسلاید تکرار می‌شود یا نه. خواندن **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## نکات

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// دنبالهٔ افکت‌ها را برای اولین اسلاید می‌گیرد
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// اولین افکت دنبالهٔ اصلی را می‌گیرد.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// زمان‌بندی/تکرار افکت را به "تا انتهای اسلاید" تغییر می‌دهد
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## مراجع

* کلاس [ITiming](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)