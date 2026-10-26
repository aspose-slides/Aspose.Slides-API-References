---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides für C++ API Referenz
description: Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Schreiben float.
type: docs
weight: 313
url: /de/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) Methode


Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Schreiben **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändert den Animieren-Texttyp des Effekts auf "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Setzt die Verzögerung zwischen animierten Textteilen auf 20% der Effektdauer.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Siehe auch

* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)