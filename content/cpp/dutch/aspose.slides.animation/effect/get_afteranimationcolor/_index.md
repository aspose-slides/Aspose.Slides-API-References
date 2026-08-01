---
title: get_AfterAnimationColor()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een kleur na animatie voor effect. Lees IColorFormat.
type: docs
weight: 248
url: /nl/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() methode


Definieert een kleur na animatie voor effect. Lees [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Verander het type na-animatie van het effect naar "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Stel de kleur na-animatie van het effect in.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColorFormat](../../../aspose.slides/icolorformat/)
* Klasse [Effect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)