---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과에 대한 애니메이트 텍스트 유형을 정의합니다. 도형 텍스트는 문자 단위, 단어 단위 또는 한 번에 모두 애니메이션될 수 있습니다. AnimateTextType을 읽으십시오.
type: docs
weight: 274
url: /ko/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() 메서드

효과에 대한 애니메이트 텍스트 유형을 정의합니다. 도형 텍스트는 문자 단위, 단어 단위 또는 한 번에 모두 애니메이션될 수 있습니다. [AnimateTextType](../../animatetexttype/)을(를) 읽으십시오.

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## 비고

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 슬라이드의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 효과 애니메이트 텍스트 유형을 "By letter"로 변경합니다.
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 참고

* 열거형 [AnimateTextType](../../animatetexttype/)
* 클래스 [Effect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)