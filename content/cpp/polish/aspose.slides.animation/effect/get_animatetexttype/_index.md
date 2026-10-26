---
title: get_AnimateTextType()
second_title: Aspose.Slides dla C++ API Reference
description: Definiuje typ animowanego tekstu dla efektu. Tekst w kształcie może być animowany literą, słowem lub jednocześnie. Przeczytaj AnimateTextType.
type: docs
weight: 274
url: /pl/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() metoda


Definiuje typ animowanego tekstu dla efektu. Tekst w kształcie może być animowany literą, słowem lub jednocześnie. Przeczytaj [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
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
* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)