---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob der Effekt bis zum nächsten Klick wiederholt wird. Schreiben Sie bool.
type: docs
weight: 170
url: /de/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) Methode

Dieses Attribut gibt an, ob der Effekt bis zum nächsten Klick wiederholt wird. Schreiben Sie **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## Hinweise

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Siehe auch

* Klasse [Timing](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)