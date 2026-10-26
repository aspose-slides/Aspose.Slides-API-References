---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API 참조
description: 숨겨진 슬라이드를 포함할지 여부를 가져오거나 설정합니다.
type: docs
weight: 40
url: /ko/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) 메서드


숨겨진 슬라이드를 포함할지 여부를 가져오거나 설정합니다.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 참고

* 클래스 [PresentationAnimationsGenerator](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)