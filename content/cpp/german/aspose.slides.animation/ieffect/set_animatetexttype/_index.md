---
title: set_AnimateTextType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabe für Buchstabe, Wort für Wort oder komplett auf einmal animiert werden. Schreiben Sie AnimateTextType.
type: docs
weight: 287
url: /de/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) Methode

Definiert einen animierten Texttyp für den Effekt. Der Text der Form kann Buchstabe für Buchstabe, Wort für Wort oder komplett auf einmal animiert werden. Schreiben Sie [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Anmerkungen

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändert den Animate-Texttyp des Effekts zu "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Siehe auch

* Aufzählung [AnimateTextType](../../animatetexttype/)
* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)