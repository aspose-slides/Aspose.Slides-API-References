---
title: set_AnimateTextType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과를 위한 애니메이트 텍스트 유형을 정의합니다. 도형 텍스트는 문자별, 단어별 또는 한 번에 모두 애니메이션될 수 있습니다. AnimateTextType을 작성합니다.
type: docs
weight: 287
url: /ko/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) 메서드


효과에 대한 애니메이트 텍스트 유형을 정의합니다. 도형 텍스트는 문자별, 단어별 또는 한 번에 모두 애니메이션될 수 있습니다. [AnimateTextType](../../animatetexttype/)를 작성합니다.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## 참고


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## 참조

* 열거형 [AnimateTextType](../../animatetexttype/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)