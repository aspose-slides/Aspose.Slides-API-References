---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 지연 시간 [ms]을 가져옵니다.
type: docs
weight: 1
url: /ko/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const 메서드


기본 지연 시간 [ms]을 가져옵니다.

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1초
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 참조

* 클래스 [PresentationAnimationsGenerator](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)