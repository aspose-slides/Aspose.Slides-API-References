---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API Reference
description: Get or sets if hidden slides should be included.
type: docs
weight: 40
url: /cpp/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(**bool**) method


Get or sets if hidden slides should be included.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## See Also

* Class [PresentationAnimationsGenerator](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
