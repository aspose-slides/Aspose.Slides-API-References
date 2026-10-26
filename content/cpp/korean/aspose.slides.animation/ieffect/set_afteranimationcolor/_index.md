---
title: set_AfterAnimationColor()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과에 대한 애프터 애니메이션 색상을 정의합니다. IColorFormat을(를) 작성합니다.
type: docs
weight: 261
url: /ko/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) 메서드


효과에 대한 애프터 애니메이션 색상을 정의합니다. [IColorFormat](../../../aspose.slides/icolorformat/)을(를) 작성합니다.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 효과의 애프터 애니메이션 유형을 "Color"로 변경합니다.
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// 효과의 애프터 애니메이션 색상을 설정합니다.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColorFormat](../../../aspose.slides/icolorformat/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)