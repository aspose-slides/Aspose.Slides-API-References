---
title: get_AdvanceAfter()
second_title: Riferimento API di Aspose.Slides per C++
description: Questo attributo indica se la presentazione avanzerà alla diapositiva successiva dopo un certo intervallo di tempo. Leggi bool.
type: docs
weight: 105
url: /it/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() metodo


Questo attributo indica se la presentazione avanzerà alla diapositiva successiva dopo un certo intervallo di tempo. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Ottieni la prima transizione della diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifica se il flag Advance Slide After è attivo
if (slideTransition->get_AdvanceAfter())
{
    // Ottieni il valore del tempo di Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Vedi anche

* Classe [ISlideShowTransition](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)