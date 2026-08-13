---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. 읽기 bool.
type: docs
weight: 196
url: /ko/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() 메서드

이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
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
    // 두 번째 효과의 Enhancements/Sound을 "Stop Previous Sound" 로 변경
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 참조

* 클래스 [Effect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)