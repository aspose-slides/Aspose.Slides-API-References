---
title: get_StopPreviousSound()
second_title: Aspose.Slides pro C++ – reference API
description: Tento atribut určuje, zda animace zastaví předchozí zvuk. Vrací bool.
type: docs
weight: 196
url: /cs/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() metoda


Tento atribut určuje, zda animace zastaví předchozí zvuk. Vrací **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
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
    // Změní druhý efekt Zlepšení/Zvuk na "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Viz také

* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)