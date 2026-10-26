---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ten atrybut określa, czy efekt będzie powtarzany aż do następnego kliknięcia. Odczyt bool.
type: docs
weight: 157
url: /pl/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() metoda


Ten atrybut określa, czy efekt będzie powtarzany aż do następnego kliknięcia. Odczyt **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Pobiera sekwencję efektów dla pierwszego slajdu
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Pobiera pierwszy efekt głównej sekwencji.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Zmienia efekt Timing/Repeat na "Do końca slajdu"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Zobacz także

* Klasa [Timing](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)