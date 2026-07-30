---
title: get_AdvanceAfter()
second_title: Aspose.Slides pro referenci API C++
description: Tento atribut určuje, zda se prezentace přesune na další snímek po uplynutí určitého času. Vrací bool.
type: docs
weight: 105
url: /cs/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISSlideShowTransition::get_AdvanceAfter() metoda

Tento atribut určuje, zda se prezentace přesune na další snímek po určitém čase. Vrací **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Získá první přechod snímku
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Zkontroluje, zda je příznak Advance Slide After zaškrtnut
if (slideTransition->get_AdvanceAfter())
{
    // Získá hodnotu času Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Viz také

* třída [ISlideShowTransition](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)