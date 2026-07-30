---
title: set_StopPreviousSound()
second_title: Aspose.Slides pro C++ referenci API
description: Tento atribut určuje, zda animace zastavuje předchozí zvuk. Zapište bool.
type: docs
weight: 209
url: /cs/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) metoda


Tento atribut určuje, zda animace zastavuje předchozí zvuk. Zapište **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
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
    // Změní druhý efekt Enhancements/Sound na "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Viz také

* Třída [Effect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)