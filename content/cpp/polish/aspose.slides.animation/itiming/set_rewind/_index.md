---
title: set_Rewind()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Zapisz bool.
type: docs
weight: 326
url: /pl/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) metoda


Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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