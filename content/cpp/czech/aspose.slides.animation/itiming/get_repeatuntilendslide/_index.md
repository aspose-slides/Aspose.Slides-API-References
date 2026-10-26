---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Vrací bool.
type: docs
weight: 131
url: /cs/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() metoda


Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Vrací **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
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

* Třída [ITiming](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)