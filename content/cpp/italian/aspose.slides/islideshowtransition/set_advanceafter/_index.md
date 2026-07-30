---
title: set_AdvanceAfter()
second_title: Riferimento API di Aspose.Slides per C++
description: Questo attributo specifica se la presentazione si sposterà alla diapositiva successiva dopo un certo periodo di tempo. Scrivi bool.
type: docs
weight: 118
url: /it/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) metodo


Questo attributo specifica se la presentazione scorrerà alla diapositiva successiva dopo un certo intervallo di tempo. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Ottieni la prima transizione della diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifica se il flag Advance Slide After è impostato
if (slideTransition->get_AdvanceAfter())
{
    // Ottieni il valore del tempo Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Vedi anche

* Classe [ISlideShowTransition](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)