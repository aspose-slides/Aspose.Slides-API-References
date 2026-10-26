---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 애니메이션 효과가 이전 사운드를 멈추는지 여부를 지정합니다. bool 형식으로 씁니다.
type: docs
weight: 209
url: /ko/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) 메서드


이 속성은 애니메이션 효과가 이전 사운드를 멈추는지 여부를 지정합니다. **bool** 형식으로 씁니다.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// 두 번째 슬라이드의 첫 번째 효과를 가져옵니다.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // 두 번째 효과의 Enhancements/Sound를 "Stop Previous Sound"로 변경합니다.
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 참조

* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)