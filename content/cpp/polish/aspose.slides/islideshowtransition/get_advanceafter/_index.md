---
title: get_AdvanceAfter()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Zwraca bool.
type: docs
weight: 105
url: /pl/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() metoda

Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Zwraca **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
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

* Klasa [ISlideShowTransition](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)