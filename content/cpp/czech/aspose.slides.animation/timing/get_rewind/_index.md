---
title: get_Rewind()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Tento atribut určuje, zda se efekt po dokončení přehrávání přehraje zpět. Vrací bool.
type: docs
weight: 235
url: /cs/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() metoda


Tento atribut určuje, zda se efekt po dokončení přehrávání přehraje zpět. Vrací **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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

* Třída [Timing](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)