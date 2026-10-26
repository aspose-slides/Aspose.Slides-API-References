---
title: set_StopPreviousSound()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Zapisz bool.
type: docs
weight: 209
url: /pl/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) metoda

Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Zapisz **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
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

* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)