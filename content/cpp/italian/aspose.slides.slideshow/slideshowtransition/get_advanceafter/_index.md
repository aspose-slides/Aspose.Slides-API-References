---
title: get_AdvanceAfter()
second_title: Riferimento API Aspose.Slides per C++
description: Questo attributo specifica se la presentazione scorrerà alla diapositiva successiva dopo un certo intervallo di tempo. Leggi bool.
type: docs
weight: 105
url: /it/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() metodo


Questo attributo specifica se la presentazione scorrerà alla diapositiva successiva dopo un certo intervallo di tempo. Leggi **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Note


```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Ottieni la prima transizione della diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifica se il flag Advance Slide After è attivato
if (slideTransition->get_AdvanceAfter())
{
    // Ottieni il valore del tempo di avanzamento della diapositiva
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Vedi anche

* Classe [SlideShowTransition](../)
* Spazio dei nomi [Aspose::Slides::SlideShow](../../)
* Libreria [Aspose.Slides](../../../)