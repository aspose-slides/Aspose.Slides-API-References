---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API 참조
description: 이 속성은 효과가 다음 클릭이 있을 때까지 반복될지 여부를 지정합니다. 읽기 bool.
type: docs
weight: 157
url: /ko/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() 메서드

이 속성은 효과가 다음 클릭이 있을 때까지 반복될지 여부를 지정합니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## 참고

* 클래스 [Timing](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)