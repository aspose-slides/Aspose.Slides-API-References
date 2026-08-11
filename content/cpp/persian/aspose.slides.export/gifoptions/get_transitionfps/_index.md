---
title: get_TransitionFps()
second_title: مرجع API Aspose.Slides برای C++
description: نرخ فریم‌های انتقال را به دست می‌آورد [frames/sec] مقدار پیش‌فرض ۲۵ است.
type: docs
weight: 53
url: /fa/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() متد

نرخ فریم‌های انتقال را به‌دست می‌آورد [frames/sec]. مقدار پیش‌فرض ۲۵ است.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## مطالب مرتبط

* کلاس [GifOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)