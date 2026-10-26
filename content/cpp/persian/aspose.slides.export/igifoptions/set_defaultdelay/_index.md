---
title: set_DefaultDelay()
second_title: Aspose.Slides برای مرجع API C++
description: "تاخیر پیش‌فرض را به میلی‌ثانیه تنظیم می‌کند. این مقدار زمانی استفاده خواهد شد که متد ISlideShowTransition::set_AdvanceAfterTime() صدا زده نشده باشد. مقدار پیش‌فرض ۱۰۰۰ است."
type: docs
weight: 92
url: /fa/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) متد

تاخیر پیش‌فرض را به میلی‌ثانیه تنظیم می‌کند. این مقدار زمانی استفاده خواهد شد که متد [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) صدا زده نشده باشد. مقدار پیش‌فرض ۱۰۰۰ است.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## توضیحات

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