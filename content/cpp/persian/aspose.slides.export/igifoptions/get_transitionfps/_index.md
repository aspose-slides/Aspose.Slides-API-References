---
title: get_TransitionFps()
second_title: مرجع API Aspose.Slides برای C++
description: FPS تغییر را دریافت می‌کند [frames/sec] مقدار پیش‌فرض ۲۵ است.
type: docs
weight: 53
url: /fa/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() متد

FPS تغییر [frames/sec] را دریافت می‌کند. مقدار پیش‌فرض ۲۵ است.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## موارد مرتبط

* کلاس [IGifOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)