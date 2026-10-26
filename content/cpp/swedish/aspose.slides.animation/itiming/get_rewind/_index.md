---
title: get_Rewind()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut specificerar om effekten ska spolas tillbaka när den är klar. Läs bool.
type: docs
weight: 313
url: /sv/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() metod

Detta attribut specificerar om effekten ska spolas tillbaka när den är klar. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
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

* Klass [ITiming](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)