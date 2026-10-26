---
title: set_TransitionFps()
second_title: Aspose.Slides برای C++ – مرجع API
description: FPS انتقال را تنظیم می‌کند [frames/sec] مقدار پیش‌فرض ۲۵ است.
type: docs
weight: 66
url: /fa/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) متد

FPS انتقال را تنظیم می‌کند [frames/sec] مقدار پیش‌فرض ۲۵ است.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## توضیحات


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## مراجع دیگر

* کلاس [GifOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)