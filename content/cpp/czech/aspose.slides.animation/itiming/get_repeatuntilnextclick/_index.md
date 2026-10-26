---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Tento atribut určuje, zda se efekt bude opakovat až do dalšího kliknutí. Čte bool.
type: docs
weight: 157
url: /cs/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() metoda


Tento atribut určuje, zda se efekt bude opakovat až do dalšího kliknutí. Čte **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
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