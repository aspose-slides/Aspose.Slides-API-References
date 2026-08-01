---
title: get_AnimateTextType()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een animatieteksttype voor effect. De shape-tekst kan per letter, per woord of in één keer worden geanimeerd. Lees AnimateTextType.
type: docs
weight: 274
url: /nl/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() methode


Definieert een animatieteksttype voor effect. De shape-tekst kan per letter, per woord of in één keer worden geanimeerd. Lees [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Verander het animatieteksttype van het effect naar "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Zie ook

* Enum [AnimateTextType](../../animatetexttype/)
* Klasse [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)