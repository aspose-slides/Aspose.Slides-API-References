---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides pro referenci API C++
description: Tento atribut určuje, zda se efekt bude opakovat až do dalšího kliknutí. Zapište bool.
type: docs
weight: 170
url: /cs/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) metoda

This attribute specifies if the effect will repeat until the next click. Write **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Získá sekvenci efektů pro první snímek
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Získá první efekt hlavní sekvence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Změní Timing/Repeat efektu na "Do konce snímku"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Viz také

* Třída [ITiming](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)