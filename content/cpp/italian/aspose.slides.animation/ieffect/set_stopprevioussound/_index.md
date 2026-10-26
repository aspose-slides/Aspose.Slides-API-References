---
title: set_StopPreviousSound()
second_title: Riferimento API Aspose.Slides per C++
description: Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Scrivi bool.
type: docs
weight: 209
url: /it/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) metodo


Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Cambia il secondo effetto Enhancements/Sound in "Stop Previous Sound"
}
```

## Vedi anche

* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)