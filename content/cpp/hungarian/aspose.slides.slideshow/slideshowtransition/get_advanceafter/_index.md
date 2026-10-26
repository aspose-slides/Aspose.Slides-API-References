---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API referencia
description: Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvasható bool.
type: docs
weight: 105
url: /hu/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() metódus


Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvasható **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Az első dia átmenet lekérése
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Ellenőrzi, hogy az Advance Slide After jelző be van-e kapcsolva
if (slideTransition->get_AdvanceAfter())
{
    // Az Advance Slide After időérték lekérése
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Lásd még

* Osztály [SlideShowTransition](../)
* Névtér [Aspose::Slides::SlideShow](../../)
* Könyvtár [Aspose.Slides](../../../)