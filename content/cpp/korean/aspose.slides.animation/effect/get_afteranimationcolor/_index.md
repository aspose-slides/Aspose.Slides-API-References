---
title: get_AfterAnimationColor()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과에 대한 애니메이션 후 색상을 정의합니다. IColorFormat을 읽으십시오.
type: docs
weight: 248
url: /ko/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() 메서드

효과에 대한 애니메이션 후 색상을 정의합니다. [IColorFormat](../../../aspose.slides/icolorformat/)를 읽으십시오.

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 슬라이드의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 효과의 After animation 유형을 "Color"로 변경합니다.
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// 효과의 After animation 색상을 설정합니다.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColorFormat](../../../aspose.slides/icolorformat/)
* 클래스 [Effect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)