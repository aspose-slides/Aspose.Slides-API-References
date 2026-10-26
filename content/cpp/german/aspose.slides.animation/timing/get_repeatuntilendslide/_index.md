---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides für C++ API Referenz
description: Dieses Attribut gibt an, ob der Effekt bis zum Ende der Folie wiederholt wird. Lesen bool.
type: docs
weight: 131
url: /de/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() Methode

Dieses Attribut gibt an, ob der Effekt bis zum Ende der Folie wiederholt wird. Lesen **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## Bemerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Siehe auch

* Klasse [Timing](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)