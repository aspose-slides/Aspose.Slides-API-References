---
title: set_DefaultDelay()
second_title: مرجع API Aspose.Slides برای C++
description: تاخیر پیش‌فرض را به میلی‌ثانیه [ms] تنظیم می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) متد


تاخیر پیش‌فرض را به میلی‌ثانیه تنظیم می‌کند.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1 ثانیه
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## موارد مرتبط

* کلاس [PresentationAnimationsGenerator](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)