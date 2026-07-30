---
title: set_AdvanceAfter()
second_title: Aspose.Slides per il riferimento API di C++
description: Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. Scrivi bool.
type: docs
weight: 118
url: /it/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) metodo


Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. Scrivi **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Note



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Ottieni la prima transizione della diapositiva
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Verifica se il flag Advance Slide After è selezionato
if (slideTransition->get_AdvanceAfter())
{
    // Ottieni il valore del tempo Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Vedi anche

* Classe [SlideShowTransition](../)
* Spazio dei nomi [Aspose::Slides::SlideShow](../../)
* Libreria [Aspose.Slides](../../../)