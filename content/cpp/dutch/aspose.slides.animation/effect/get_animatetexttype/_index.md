---
title: get_AnimateTextType()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een animatieteksttype voor effect. De vormtekst kan per letter, per woord of in één keer worden geanimeerd. Lees AnimateTextType.
type: docs
weight: 274
url: /nl/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() methode

Definieert een animatieteksttype voor effect. De vormtekst kan per letter, per woord of in één keer worden geanimeerd. Lees [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Zie ook

* Enum [AnimateTextType](../../animatetexttype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)