---
title: get_DefaultDelay()
second_title: مرجع API Aspose.Slides برای C++
description: "زمان تأخیر پیش‌فرض [ms] را دریافت می‌کند. اگر متد ISlideShowTransition::set_AdvanceAfterTime() صدا زده نشده باشد، این مقدار استفاده خواهد شد. مقدار پیش‌فرض 1000 است."
type: docs
weight: 79
url: /fa/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() متد


زمان تأخیر پیش‌فرض [ms] را دریافت می‌کند. این مقدار در صورتی استفاده خواهد شد که متد [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) صدا زده نشده باشد. مقدار پیش‌فرض 1000 است.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## نکات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## موارد مرتبط

* کلاس [IGifOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)