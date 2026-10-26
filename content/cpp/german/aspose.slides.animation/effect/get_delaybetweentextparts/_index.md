---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Lese float.
type: docs
weight: 300
url: /de/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() Methode


Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Lesen **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## Anmerkungen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hole den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändere den Effekt Animate text type zu "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Setze die Verzögerung zwischen animierten Textparts auf 20% der Effektdauer.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Siehe auch

* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)