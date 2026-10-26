---
title: get_AnimateTextType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabenweise, Wortweise oder gleichzeitig animiert werden. Lesen Sie AnimateTextType.
type: docs
weight: 274
url: /de/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() Methode


Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabenweise, Wortweise oder gleichzeitig animiert werden. Lesen [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändere den Animations-Texttyp des Effekts zu "Nach Buchstaben"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Siehe auch

* Enum [AnimateTextType](../../animatetexttype/)
* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)