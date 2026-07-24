---
title: get_AnimateTextType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabe für Buchstabe, Wort für Wort oder vollständig auf einmal animiert werden. Lesen Sie AnimateTextType.
type: docs
weight: 274
url: /de/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() Methode


Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabe für Buchstabe, Wort für Wort oder komplett auf einmal animiert werden. Lesen Sie [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Anmerkungen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Erhalte den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändere den Animate-Texttyp des Effekts auf "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Siehe auch

* Aufzählung [AnimateTextType](../../animatetexttype/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)