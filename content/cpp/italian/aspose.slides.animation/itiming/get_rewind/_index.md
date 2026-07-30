---
title: get_Rewind()
second_title: Riferimento API Aspose.Slides per C++
description: Questo attributo specifica se l'effetto tornerà indietro al termine della riproduzione. Leggi bool.
type: docs
weight: 313
url: /it/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() metodo

Questo attributo specifica se l'effetto tornerà indietro al termine della riproduzione. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Vedi anche

* Classe [ITiming](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)