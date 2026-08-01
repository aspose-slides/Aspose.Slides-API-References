---
title: get_AfterAnimationColor()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een kleur na animatie voor effect. Lees IColorFormat.
type: docs
weight: 248
url: /nl/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() methode


Definieert een kleur na animatie voor effect. Lees [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColorFormat](../../../aspose.slides/icolorformat/)
* Klasse [IEffect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)