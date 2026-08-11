---
title: set_TransitionFps()
second_title: مرجع API Aspose.Slides برای C++
description: FPS انتقال را تنظیم می‌کند [frames/sec] مقدار پیش‌فرض ۲۵ است.
type: docs
weight: 66
url: /fa/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) متد


FPS انتقال را تنظیم می‌کند [frames/sec] مقدار پیش‌فرض ۲۵ است.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
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