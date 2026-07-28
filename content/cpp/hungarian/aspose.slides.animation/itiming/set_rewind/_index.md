---
title: set_Rewind()
second_title: Aspose.Slides C++ API referencia
description: Ez az attribútum meghatározza, hogy a hatás visszatekerődik-e a lejátszás befejezése után. Írja bool.
type: docs
weight: 326
url: /hu/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) metódus

Ez az attribútum meghatározza, hogy a hatás visszatekerődik-e a lejátszás befejezése után. Írja **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

* Osztály [ITiming](../)
* Névterület [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)