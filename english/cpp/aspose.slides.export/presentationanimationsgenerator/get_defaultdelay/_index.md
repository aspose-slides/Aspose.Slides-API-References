---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API Reference
description: Gets default delay time [ms].
type: docs
weight: 1
url: /cpp/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const method


Gets default delay time [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## See Also

* Class [PresentationAnimationsGenerator](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
