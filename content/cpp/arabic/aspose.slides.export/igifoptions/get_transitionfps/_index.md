---
title: get_TransitionFps()
second_title: مرجع API Aspose.Slides لـ C++
description: يحصل على عدد إطارات الانتقال [frames/sec] القيمة الافتراضية هي 25.
type: docs
weight: 53
url: /ar/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() طريقة


يحصل على عدد إطارات الانتقال [frames/sec] القيمة الافتراضية هي 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## انظر أيضًا

* الفئة [IGifOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)