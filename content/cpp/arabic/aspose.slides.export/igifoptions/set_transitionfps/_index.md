---
title: set_TransitionFps()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط عدد إطارات الانتقال [frames/sec] القيمة الافتراضية هي 25.
type: docs
weight: 66
url: /ar/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) طريقة

يضبط عدد إطارات الانتقال [frames/sec] القيمة الافتراضية هي 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## انظر أيضًا

* فئة [IGifOptions](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)