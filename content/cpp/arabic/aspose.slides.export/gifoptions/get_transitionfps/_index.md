---
title: get_TransitionFps()
second_title: Aspose.Slides لمرجع API C++
description: يعيد عدد إطارات الانتقال [frames/sec] القيمة الافتراضية هي 25.
type: docs
weight: 53
url: /ar/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() طريقة


يعيد عدد إطارات الانتقال [frames/sec] القيمة الافتراضية هي 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
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
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)