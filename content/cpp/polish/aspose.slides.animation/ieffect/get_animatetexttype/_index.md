---
title: get_AnimateTextType()
second_title: Aspose.Slides dla C++ – referencja API
description: Definiuje typ animowanego tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub jednocześnie. Przeczytaj AnimateTextType.
type: docs
weight: 274
url: /pl/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() metoda

Definiuje typ animowanego tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub całościowo. Zobacz [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Uwagi

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Pobierz pierwszy efekt pierwszego slajdu.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Zmień typ animowanego tekstu efektu na "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Zobacz także

* Wyliczenie [AnimateTextType](../../animatetexttype/)
* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)