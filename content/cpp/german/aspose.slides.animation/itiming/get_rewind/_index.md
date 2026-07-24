---
title: get_Rewind()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückgespult wird. Lesen bool.
type: docs
weight: 313
url: /de/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() Methode


Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückgespult wird. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Siehe auch

* Klasse [ITiming](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)