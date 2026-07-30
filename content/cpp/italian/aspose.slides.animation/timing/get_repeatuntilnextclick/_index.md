---
title: get_RepeatUntilNextClick()
second_title: Riferimento API Aspose.Slides per C++
description: Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. Leggi bool.
type: docs
weight: 157
url: /it/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() metodo


Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. Leggi **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Vedi anche

* Classe [Timing](../)
* Namespace [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)