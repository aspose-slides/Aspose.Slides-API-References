---
title: get_RepeatUntilEndSlide()
second_title: Riferimento API di Aspose.Slides per C++
description: Questo attributo specifica se l'effetto verrà ripetuto fino alla fine della diapositiva. Leggi bool.
type: docs
weight: 131
url: /it/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() metodo


Questo attributo specifica se l'effetto verrà ripetuto fino alla fine della diapositiva. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Osservazioni



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

* Classe [ITiming](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)