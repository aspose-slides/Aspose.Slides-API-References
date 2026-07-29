---
title: get_StopPreviousSound()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut specificerar om animationseffekten stoppar det föregående ljudet. Läs bool.
type: docs
weight: 196
url: /sv/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() metod


Detta attribut specificerar om animationseffekten stoppar det föregående ljudet. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
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

## Se också

* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)