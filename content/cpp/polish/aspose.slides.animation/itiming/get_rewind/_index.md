---
title: get_Rewind()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Odczytaj bool.
type: docs
weight: 313
url: /pl/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() metoda

Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Odczytaj **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Zobacz także

* Klasa [ITiming](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)