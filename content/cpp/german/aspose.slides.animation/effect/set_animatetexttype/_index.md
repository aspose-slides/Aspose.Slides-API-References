---
title: set_AnimateTextType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabe für Buchstabe, Wort für Wort oder gleichzeitig animiert werden. Schreiben Sie AnimateTextType.
type: docs
weight: 287
url: /de/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) Methode

Definiert einen animierten Texttyp für den Effekt. Der Form-Text kann Buchstabe für Buchstabe, Wort für Wort oder gleichzeitig animiert werden. Schreiben Sie [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Bemerkungen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Siehe Auch

* Enum [AnimateTextType](../../animatetexttype/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)