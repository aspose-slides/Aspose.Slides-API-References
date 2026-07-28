---
title: get_AdvanceAfter()
second_title: Aspose.Slides – Referencja API C++
description: Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Odczyt bool.
type: docs
weight: 105
url: /pl/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() metoda


Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Odczyt **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Pobierz pierwsze przejście slajdu
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Sprawdź, czy flaga Advance Slide After jest zaznaczona
if (slideTransition->get_AdvanceAfter())
{
    // Pobierz wartość czasu Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Zobacz także

* Klasa [SlideShowTransition](../)
* Przestrzeń nazw [Aspose::Slides::SlideShow](../../)
* Biblioteka [Aspose.Slides](../../../)