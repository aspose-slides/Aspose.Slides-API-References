---
title: set_Rewind()
second_title: Aspose.Slides pro C++ - reference API
description: Tento atribut určuje, zda se efekt po dokončení přehrávání přehraje zpět. Zapisovat bool.
type: docs
weight: 248
url: /cs/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) metoda

Tento atribut určuje, zda se efekt po dokončení přehrávání přehraje zpět. Zapisovat **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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