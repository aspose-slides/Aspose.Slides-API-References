---
title: get_AdvanceAfter()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om bildspelet kommer att gå till nästa bild efter en viss tid. Läs bool.
type: docs
weight: 105
url: /sv/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() metod

Detta attribut anger om bildspelet kommer att gå till nästa bild efter en viss tid. Läs **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Hämta den första bildövergången
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Kontrollera om flaggan Advance Slide After är markerad
if (slideTransition->get_AdvanceAfter())
{
    // Hämta värdet för Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Se också

* Klass [SlideShowTransition](../)
* Namnrymd [Aspose::Slides::SlideShow](../../)
* Bibliotek [Aspose.Slides](../../../)