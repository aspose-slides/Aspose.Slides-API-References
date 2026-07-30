---
title: get_StopPreviousSound()
second_title: Aspose.Slides pro C++ API Reference
description: Tento atribut určuje, zda animace efekt zastavuje předchozí zvuk. Číst bool.
type: docs
weight: 196
url: /cs/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() metoda


Tento atribut určuje, zda animace efekt zastavuje předchozí zvuk. Číst **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt prvního snímku.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Získá první efekt druhého snímku.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Změní Enhancements/Sound druhého efektu na "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Viz také

* Třída [Effect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)