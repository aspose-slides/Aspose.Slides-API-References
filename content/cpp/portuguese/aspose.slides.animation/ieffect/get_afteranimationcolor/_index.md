---
title: get_AfterAnimationColor()
second_title: Referência da API Aspose.Slides para C++
description: Define uma cor de animação após o efeito. Leia IColorFormat.
type: docs
weight: 248
url: /pt/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() método


Define uma cor de animação após o efeito. Leia [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorFormat](../../../aspose.slides/icolorformat/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)