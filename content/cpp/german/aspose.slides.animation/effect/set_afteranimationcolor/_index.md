---
title: set_AfterAnimationColor()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert eine Nach-Animationsfarbe für den Effekt. Schreiben Sie IColorFormat.
type: docs
weight: 261
url: /de/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) Methode

Definiert eine Nach-Animationsfarbe für den Effekt. Schreiben Sie [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## Hinweise


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColorFormat](../../../aspose.slides/icolorformat/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)