---
title: set_RepeatUntilEndSlide()
second_title: Riferimento API di Aspose.Slides per C++
description: Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. Scrivi bool.
type: docs
weight: 144
url: /it/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) metodo


Questo attributo specifica se l'effetto si ripetterà fino alla fine della diapositiva. Scrivi **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## Note



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Vedi anche

* Classe [Timing](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)