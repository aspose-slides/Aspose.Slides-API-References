---
title: set_AdvanceAfter()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Zapisz bool.
type: docs
weight: 118
url: /pl/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) metoda


Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Zapisz **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Pobierz pierwsze przejście slajdu
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Sprawdź, czy flaga Advance Slide After jest ustawiona
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