---
title: set_AfterAnimationColor()
second_title: Aspose.Slides C++ API 참조
description: 효과에 대한 애니메이션 후 색상을 정의합니다. IColorFormat을 씁니다.
type: docs
weight: 261
url: /ko/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) 메서드


효과에 대한 애니메이션 이후 색상을 정의합니다. [IColorFormat](../../../aspose.slides/icolorformat/)을 씁니다.

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
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

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColorFormat](../../../aspose.slides/icolorformat/)
* 클래스 [Effect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)