---
title: get_AdvanceAfter()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om bildspelet kommer att gå till nästa bild efter en viss tid. Läs bool.
type: docs
weight: 105
url: /sv/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() metod


Detta attribut anger om bildspelet kommer att gå till nästa bild efter en viss tid. Läs **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
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

## Se även

* Klass [ISlideShowTransition](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)