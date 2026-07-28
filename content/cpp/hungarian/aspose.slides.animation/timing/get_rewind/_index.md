---
title: get_Rewind()
second_title: Aspose.Slides C++ API-referencia
description: Ez a tulajdonság meghatározza, hogy a hatás lejátszása befejezése után visszatekerődik-e. Olvasható bool.
type: docs
weight: 235
url: /hu/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() metódus


Ez a tulajdonság meghatározza, hogy a hatás lejátszása befejezése után visszatekerődik-e. Olvasható **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Lásd még

* Osztály [Timing](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)