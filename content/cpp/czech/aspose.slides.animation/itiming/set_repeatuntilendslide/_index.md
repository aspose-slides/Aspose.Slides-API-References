---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides pro C++ API Reference
description: Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Zapište bool.
type: docs
weight: 144
url: /cs/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) metoda


Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Viz také

* Třída [ITiming](../)
* Obor názvů [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)