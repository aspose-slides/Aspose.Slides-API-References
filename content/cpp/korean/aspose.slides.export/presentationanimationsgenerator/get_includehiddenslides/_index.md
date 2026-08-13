---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 숨겨진 슬라이드를 포함할지 여부를 가져오거나 설정합니다.
type: docs
weight: 27
url: /ko/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const method


숨겨진 슬라이드를 포함할지 여부를 가져오거나 설정합니다.

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