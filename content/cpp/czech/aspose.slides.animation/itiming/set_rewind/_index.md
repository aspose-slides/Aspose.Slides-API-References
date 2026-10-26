---
title: set_Rewind()
second_title: Aspose.Slides pro C++ API Reference
description: Tento atribut určuje, zda se efekt po dokončení přehrávání přehraje zpět. Zapište bool.
type: docs
weight: 326
url: /cs/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) metoda


Tento atribut určuje, zda se efekt po dokončení přehrávání přehraje zpět. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Viz také

* Třída [ITiming](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)