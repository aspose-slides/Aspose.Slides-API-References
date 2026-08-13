---
title: get_AfterAnimationColor()
second_title: Aspose.Slides C++ API 레퍼런스
description: 효과에 대한 사후 애니메이션 색상을 정의합니다. IColorFormat을 읽어보세요.
type: docs
weight: 248
url: /ko/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() 메서드

효과에 대한 사후 애니메이션 색상을 정의합니다. [IColorFormat](../../../aspose.slides/icolorformat/)를 읽어보십시오.

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColorFormat](../../../aspose.slides/icolorformat/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)