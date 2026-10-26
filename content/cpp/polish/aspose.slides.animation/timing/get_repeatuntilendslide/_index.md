---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Ten atrybut określa, czy efekt będzie powtarzany do końca slajdu. Odczyt **bool**.
type: docs
weight: 131
url: /pl/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() metoda


Ten atrybut określa, czy efekt będzie powtarzany do końca slajdu. Odczyt **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Zobacz także

* Klasa [Timing](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)