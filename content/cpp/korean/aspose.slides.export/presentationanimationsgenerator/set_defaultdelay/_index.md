---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API 참조
description: 기본 지연 시간을 [ms]로 설정합니다.
type: docs
weight: 14
url: /ko/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) 메서드


기본 지연 시간을 [ms]로 설정합니다.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1초
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 관련 항목

* 클래스 [PresentationAnimationsGenerator](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)