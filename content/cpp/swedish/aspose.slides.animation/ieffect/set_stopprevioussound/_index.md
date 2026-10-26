---
title: set_StopPreviousSound()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om animationseffekten stoppar det föregående ljudet. Skriv bool.
type: docs
weight: 209
url: /sv/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) metod


Detta attribut anger om animationseffekten stoppar det föregående ljudet. Skriv **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
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
    // Ändra den andra effekten Enhancements/Sound till "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Se även

* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)