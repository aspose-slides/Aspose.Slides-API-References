---
title: get_AfterAnimationColor()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert eine Nachanimationsfarbe für den Effekt. Lesen Sie IColorFormat.
type: docs
weight: 248
url: /de/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() Methode

Definiert eine Nachanimationsfarbe für den Effekt. Lesen Sie [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Anmerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändert den AfterAnimationType des Effekts zu "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Setzt die AfterAnimationColor des Effekts.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColorFormat](../../../aspose.slides/icolorformat/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)