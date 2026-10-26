---
title: set_AdvanceAfter()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Skriv bool.
type: docs
weight: 118
url: /sv/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) metod


Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Skriv **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
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