---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API 참조
description: 이 속성은 효과가 슬라이드 끝까지 반복될지 여부를 지정합니다. bool을 읽습니다.
type: docs
weight: 131
url: /ko/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() 메서드

이 속성은 효과가 슬라이드 끝까지 반복될지 여부를 지정합니다. **bool**을(를) 읽습니다.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 참고

* 클래스 [Timing](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)