---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API Reference
description: Get or sets if hidden slides should be included.
type: docs
weight: 27
url: /cpp/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const method


Get or sets if hidden slides should be included.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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
