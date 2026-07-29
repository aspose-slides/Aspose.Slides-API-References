---
title: get_AnimateTextType()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en animerad texttyp för effekt. Formtexten kan animeras per bokstav, per ord eller hela på en gång. Läs AnimateTextType.
type: docs
weight: 274
url: /sv/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() metod


Definierar en animerad texttyp för effekt. Formtexten kan animeras per bokstav, per ord eller hela på en gång. Läs [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra effektens Animate text type till "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Se även

* Enum [AnimateTextType](../../animatetexttype/)
* Klass [Effect](../)
* Namnutrymme [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)