---
title: set_AdvanceAfter()
second_title: Aspose.Slides pro C++ - reference API
description: Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Zapište bool.
type: docs
weight: 118
url: /cs/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) metoda

Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Zapište **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Poznámky


```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Získá první přechod snímku
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Zkontroluje, zda je nastaven příznak Advance Slide After
if (slideTransition->get_AdvanceAfter())
{
    // Získá hodnotu času Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Viz také

* Třída [ISlideShowTransition](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)