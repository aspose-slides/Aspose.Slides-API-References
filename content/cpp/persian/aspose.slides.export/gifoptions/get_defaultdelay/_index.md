---
title: get_DefaultDelay()
second_title: Aspose.Slides برای مرجع API C++
description: "زمان تاخیر پیش‌فرض را به‌دست می‌آورد [ms]. این مقدار در صورتی استفاده خواهد شد که متد ISlideShowTransition::set_AdvanceAfterTime() صدا زده نشده باشد. مقدار پیش‌فرض 1000 است."
type: docs
weight: 79
url: /fa/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() method


زمان تاخیر پیش‌فرض را به‌دست می‌آورد [ms]. این مقدار در صورتی استفاده خواهد شد که متد [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) صدا زده نشده باشد. مقدار پیش‌فرض ۱۰۰۰ است.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## موارد مرتبط

* کلاس [GifOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)