---
title: get_AfterAnimationColor()
second_title: Referência da API Aspose.Slides para C++
description: Define uma cor de animação posterior para o efeito. Consulte IColorFormat.
type: docs
weight: 248
url: /pt/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() método

Define uma cor de animação posterior para o efeito. Consulte [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
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
* Classe [IColorFormat](../../../aspose.slides/icolorformat/)
* Classe [Effect](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)