---
title: set_Rewind()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om effekten ska spola tillbaka när den är klar med spelning. Skriv bool.
type: docs
weight: 248
url: /sv/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) metod


Detta attribut anger om effekten ska spola tillbaka när den är klar med spelning. Skriv **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Se även

* Klass [Timing](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)