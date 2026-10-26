---
title: get_Rewind()
second_title: Riferimento API di Aspose.Slides per C++
description: Questo attributo specifica se l'effetto verrà riportato indietro al termine della riproduzione. Lettura **bool**.
type: docs
weight: 235
url: /it/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() metodo


Questo attributo specifica se l'effetto verrà riportato indietro al termine della riproduzione. Lettura **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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

* Classe [Timing](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)