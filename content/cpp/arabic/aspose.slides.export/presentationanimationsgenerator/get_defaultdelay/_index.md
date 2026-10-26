---
title: get_DefaultDelay()
second_title: مرجع API Aspose.Slides للغة C++
description: يسترجع زمن التأخير الافتراضي [ms].
type: docs
weight: 1
url: /ar/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const طريقة


يسترجع زمن التأخير الافتراضي [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## انظر أيضًا

* الفئة [PresentationAnimationsGenerator](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)