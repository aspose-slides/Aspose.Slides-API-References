---
title: set_AdvanceAfter()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Zapište bool.
type: docs
weight: 118
url: /cs/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) metoda


Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Zapište **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Poznámky


```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Získá první přechod snímku
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Zkontroluje, zda je zaškrtnut příznak Advance Slide After
if (slideTransition->get_AdvanceAfter())
{
    // Získá hodnotu Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Viz také

* Třída [SlideShowTransition](../)
* Jmenný prostor [Aspose::Slides::SlideShow](../../)
* Knihovna [Aspose.Slides](../../../)