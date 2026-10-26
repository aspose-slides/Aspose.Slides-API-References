---
title: set_DefaultDelay()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط وقت التأخير الافتراضي [ms].
type: docs
weight: 14
url: /ar/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) طريقة


يضبط وقت التأخير الافتراضي [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1 ثانية
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## انظر أيضًا

* فئة [PresentationAnimationsGenerator](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)