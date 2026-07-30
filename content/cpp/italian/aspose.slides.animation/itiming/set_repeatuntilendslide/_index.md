---
title: set_RepeatUntilEndSlide()
second_title: Riferimento API Aspose.Slides per C++
description: Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. Scrivi bool.
type: docs
weight: 144
url: /it/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) metodo

Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Ottiene la sequenza di effetti per la prima diapositiva
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Ottiene il primo effetto della sequenza principale.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Modifica il Timing/Repeat dell'effetto in "Fino alla fine della diapositiva"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Vedi anche

* Classe [ITiming](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)