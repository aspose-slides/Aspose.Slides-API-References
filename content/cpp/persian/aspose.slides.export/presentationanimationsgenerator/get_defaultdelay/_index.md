---
title: get_DefaultDelay()
second_title: مرجع API Aspose.Slides برای C++
description: زمان تأخیر پیش‌فرض را به میلی‌ثانیه [ms] بر می‌گرداند.
type: docs
weight: 1
url: /fa/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const متد


زمان تأخیر پیش‌فرض را به میلی‌ثانیه [ms] بر می‌گرداند.

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## توضییات



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1 ثانیه
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## مراجع

* کلاس [PresentationAnimationsGenerator](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)