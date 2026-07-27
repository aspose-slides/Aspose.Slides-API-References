---
title: set_AfterAnimationColor()
second_title: Referência da API Aspose.Slides para C++
description: Define uma cor após a animação para o efeito. Escreva IColorFormat.
type: docs
weight: 261
url: /pt/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) método


Define uma cor após a animação para o efeito. Escreva [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
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

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColorFormat](../../../aspose.slides/icolorformat/)
* Classe [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)