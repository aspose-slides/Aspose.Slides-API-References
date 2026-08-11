---
title: set_TransitionFps()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط عدد الإطارات في الثانية للانتقال [frames/sec] القيمة الافتراضية هي 25.
type: docs
weight: 66
url: /ar/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) طريقة


يضبط FPS الانتقال [frames/sec] القيمة الافتراضية هي 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## انظر أيضًا

* فئة [GifOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)