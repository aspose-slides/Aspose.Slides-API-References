---
title: set_AnimateTextType()
second_title: Aspose.Slides dla C++ odniesienie API
description: Definiuje typ animowanego tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub jednocześnie. Zapisz AnimateTextType.
type: docs
weight: 287
url: /pl/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metoda

Definiuje typ animowanego tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub jednocześnie. Zapisz [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Uwagi

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Zobacz także

* Wyliczenie [AnimateTextType](../../animatetexttype/)
* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)