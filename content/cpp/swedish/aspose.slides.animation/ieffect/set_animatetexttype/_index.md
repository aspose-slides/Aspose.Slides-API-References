---
title: set_AnimateTextType()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en animerad texttyp för effekt. Formtexten kan animeras per bokstav, per ord eller hela på en gång. Skriv AnimateTextType.
type: docs
weight: 287
url: /sv/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metod


Definierar en animerad texttyp för effekt. Formtexten kan animeras per bokstav, per ord eller hela på en gång. Skriv [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Se även

* Enum [AnimateTextType](../../animatetexttype/)
* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)