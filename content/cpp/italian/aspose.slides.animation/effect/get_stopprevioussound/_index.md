---
title: get_StopPreviousSound()
second_title: Riferimento API Aspose.Slides per C++
description: Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Leggi bool.
type: docs
weight: 196
url: /it/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() metodo

Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Leggi **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## Osservazioni


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Ottieni il primo effetto della seconda diapositiva.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Modifica il secondo effetto Enhancements/Sound in "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Vedi anche

* Classe [Effect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)