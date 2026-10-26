---
title: set_AfterAnimationColor()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een kleur na animatie voor het effect. Schrijf IColorFormat.
type: docs
weight: 261
url: /nl/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) methode

Definieert een kleur na animatie voor het effect. Schrijf [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## Opmerkingen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haalt het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Verander het After animation type van het effect naar "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Stel de After animation kleur van het effect in.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColorFormat](../../../aspose.slides/icolorformat/)
* Klasse [IEffect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)