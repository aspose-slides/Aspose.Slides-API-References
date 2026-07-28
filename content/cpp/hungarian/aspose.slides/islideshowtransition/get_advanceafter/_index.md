---
title: get_AdvanceAfter()
second_title: Aspose.Slides C++ API referencia
description: Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvassa a bool értéket.
type: docs
weight: 105
url: /hu/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() metódus


Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvassa a **bool** értéket.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Az első dia átmenet lekérése
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Ellenőrizze, hogy az Advance Slide After jelző be van-e állítva
if (slideTransition->get_AdvanceAfter())
{
    // Az Advance Slide After időértékének lekérése
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Lásd még

* Osztály [ISlideShowTransition](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)