---
title: set_RepeatUntilNextClick()
second_title: Riferimento API Aspose.Slides per C++
description: Questo attributo specifica se l'effetto verrà ripetuto fino al prossimo clic. Scrivi bool.
type: docs
weight: 170
url: /it/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) metodo


Questo attributo specifica se l'effetto verrà ripetuto fino al prossimo clic. Scrivi **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
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
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)