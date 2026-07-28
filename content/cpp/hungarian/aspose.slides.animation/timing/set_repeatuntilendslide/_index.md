---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides C++ API Referencia
description: Ez az attribútum meghatározza, hogy a hatás a dia végéig ismétlődik-e. Írjon bool értéket.
type: docs
weight: 144
url: /hu/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) metódus

Ez a attribútum meghatározza, hogy a hatás ismétlődik-e a dia végéig. Írja be **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## Megjegyzések

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Lásd még

* Osztály [Timing](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)