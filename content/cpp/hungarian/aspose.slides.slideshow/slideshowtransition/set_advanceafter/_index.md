---
title: set_AdvanceAfter()
second_title: Aspose.Slides C++ API Referencia
description: Ez a tulajdonság meghatározza, hogy a diavetítés bizonyos idő után a következő diára lép-e. Írja bool.
type: docs
weight: 118
url: /hu/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) method


Ez a tulajdonság meghatározza, hogy a diavetítés bizonyos idő után a következő diára lép-e. Írja **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Az első diaátmenet lekérése
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Ellenőrizze, hogy az Advance Slide After jelző be van-e állítva
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