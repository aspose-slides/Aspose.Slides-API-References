---
title: set_StopPreviousSound()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om animationseffekten stoppar det föregående ljudet. Skriv bool.
type: docs
weight: 209
url: /sv/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) metod


Detta attribut anger om animationseffekten stoppar det föregående ljudet. Skriv **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Hämta den första effekten på den andra bilden.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Ändra den andra effektens Förbättringar/Ljud till "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Se även

* Klass [Effect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)