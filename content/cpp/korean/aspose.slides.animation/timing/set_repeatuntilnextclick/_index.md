---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides C++ API 레퍼런스
description: 이 속성은 효과가 다음 클릭까지 반복될지 여부를 지정합니다. bool 형식으로 작성합니다.
type: docs
weight: 170
url: /ko/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) 메서드


이 속성은 효과가 다음 클릭까지 반복될지 여부를 지정합니다. **bool** 형식으로 씁니다.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
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

## 참조

* 클래스 [Timing](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)