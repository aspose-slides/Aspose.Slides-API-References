---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides C++ API hivatkozás
description: Ez az attribútum meghatározza, hogy a hatás a dia végéig ismétlődik-e. Olvasás bool.
type: docs
weight: 131
url: /hu/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() metódus


Ez az attribútum meghatározza, hogy a hatás a dia végéig ismétlődik-e. Olvasás **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
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