---
title: set_DefaultDelay()
second_title: Aspose.Slides برای C++ مرجع API
description: "تاخیر پیش‌فرض را به [ms] تنظیم می‌کند. اگر متد ISlideShowTransition::set_AdvanceAfterTime() صدا زده نشود، این مقدار استفاده می‌شود. مقدار پیش‌فرض 1000 است."
type: docs
weight: 92
url: /fa/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) متد

تاخیر پیش‌فرض را به [ms] تنظیم می‌کند. اگر [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) متد صدا زده نشود، این مقدار استفاده می‌شود. مقدار پیش‌فرض ۱۰۰۰ است.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
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