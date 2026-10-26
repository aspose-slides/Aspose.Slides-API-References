---
title: set_Rewind()
second_title: Riferimento API di Aspose.Slides per C++
description: Questo attributo specifica se l'effetto verrà riavvolto al termine della riproduzione. Scrivi bool.
type: docs
weight: 248
url: /it/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) metodo

Questo attributo specifica se l'effetto verrà riavvolto al termine della riproduzione. Scrivi **bool**.

```cpp
void Aspore::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Note

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