---
title: set_Rewind()
second_title: Aspose.Slides C++ API-referencia
description: Ez az attribútum meghatározza, hogy a hatás visszatekerni-e a lejátszás befejezésekor. Írja bool.
type: docs
weight: 248
url: /hu/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) metódus


Ez az attribútum meghatározza, hogy a hatás visszatekerődik-e a lejátszás befejezésekor. Írja **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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