---
title: get_AdvanceAfter()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Tento atribut určuje, zda se prezentace po určité době přesune na další snímek. Vrací bool.
type: docs
weight: 105
url: /cs/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() metoda

Tento atribut určuje, zda se prezentace po určité době přesune na další snímek. Vrací **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Získá první přechod snímku
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Zkontrolujte, zda je příznak Advance Slide After zaškrtnut
if (slideTransition->get_AdvanceAfter())
{
    // Získá hodnotu Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Viz také

* třída [SlideShowTransition](../)
* jmenný prostor [Aspose::Slides::SlideShow](../../)
* Library [Aspose.Slides](../../../)