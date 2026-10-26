---
title: get_StopPreviousSound()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ta właściwość określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Odczyt bool.
type: docs
weight: 196
url: /pl/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() metoda


To właściwość określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Pobierz pierwszy efekt pierwszego slajdu.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Pobierz pierwszy efekt drugiego slajdu.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Zmień drugi efekt Enhancements/Sound na "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Zobacz także

* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)