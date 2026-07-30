---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides pro C++ - reference API
description: Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Zapište bool.
type: docs
weight: 144
url: /cs/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) metoda


Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Zapište **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Získá sekvenci efektů pro první snímek
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Získá první efekt hlavní sekvence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Změní Timing/Repeat efektu na "Do konce snímku"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Viz také

* Třída [Timing](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)