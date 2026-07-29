---
title: get_AnimateTextType()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en animerad texttyp för effekt. Formens text kan animeras per bokstav, per ord eller hela på en gång. Läs AnimateTextType.
type: docs
weight: 274
url: /sv/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() metod


Definierar en animerad texttyp för effekt. Texten i formen kan animeras per bokstav, per ord eller hela på en gång. Läs [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra effektens Animate text type till "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Se också

* Enum [AnimateTextType](../../animatetexttype/)
* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)