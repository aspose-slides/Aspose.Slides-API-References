---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. bool 형식으로 씁니다.
type: docs
weight: 209
url: /ko/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) 메서드


이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. **bool** 형식으로 씁니다.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // 두 번째 효과의 Enhancements/Sound를 "Stop Previous Sound"으로 변경합니다.
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 참고

* 클래스 [Effect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)