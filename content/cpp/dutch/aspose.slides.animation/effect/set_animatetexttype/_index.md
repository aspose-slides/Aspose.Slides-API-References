---
title: set_AnimateTextType()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een animatieteksttype voor effect. De vormtekst kan per letter, per woord of in één keer worden geanimeerd. Schrijf AnimateTextType.
type: docs
weight: 287
url: /nl/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) methode

Definieert een animatieteksttype voor effect. De vormtekst kan per letter, per woord of in één keer worden geanimeerd. Schrijf [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Opmerkingen

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Wijzig het animatieteksttype van het effect naar "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Zie ook

* Enum [AnimateTextType](../../animatetexttype/)
* Klasse [Effect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)