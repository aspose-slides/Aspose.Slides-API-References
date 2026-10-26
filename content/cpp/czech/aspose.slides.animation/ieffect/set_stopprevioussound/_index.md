---
title: set_StopPreviousSound()
second_title: Aspose.Slides pro C++ – API reference
description: Tento atribut určuje, zda animace zastaví předchozí zvuk. Zapište bool.
type: docs
weight: 209
url: /cs/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) metoda


Tento atribut určuje, zda animace zastaví předchozí zvuk. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Poznámky


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt první snímku.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Získá první efekt druhého snímku.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Změní druhý efekt Vylepšení/Zvuk na "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Viz také

* Třída [IEffect](../)
* Obor jmen [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)