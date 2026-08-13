---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API 참조
description: 효과에 대한 애니메이트 텍스트 유형을 정의합니다. 도형 텍스트는 문자별, 단어별, 또는 한 번에 전체가 애니메이트될 수 있습니다. AnimateTextType을 읽으십시오.
type: docs
weight: 274
url: /ko/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() 메서드


효과에 대한 애니메이트 텍스트 유형을 정의합니다. 도형 텍스트는 문자별, 단어별, 또는 한 번에 전체가 애니메이트될 수 있습니다. [AnimateTextType](../../animatetexttype/)을(를) 읽으십시오.

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## 비고



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 효과의 Animate 텍스트 유형을 "by letter" 로 변경합니다.
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 참고

* 열거형 [AnimateTextType](../../animatetexttype/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)