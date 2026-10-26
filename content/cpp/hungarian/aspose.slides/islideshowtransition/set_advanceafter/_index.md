---
title: set_AdvanceAfter()
second_title: Aspose.Slides C++ API referencia
description: Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után átlép-e a következő diára. Írja bool.
type: docs
weight: 118
url: /hu/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) metódus


Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után átlép-e a következő diára. Írja **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Az első dia átmenetének lekérése
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Ellenőrzi, hogy az Advance Slide After jelző be van-e jelölve
if (slideTransition->get_AdvanceAfter())
{
    // Az Advance Slide After időértékének lekérése
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Lásd még

* Osztály [ISlideShowTransition](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)