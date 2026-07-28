---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API referenciája
description: Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Írja bool.
type: docs
weight: 209
url: /hu/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) metódus


Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Írja **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Módosítsa a második effektus Enhancements/Sound értékét "Stop Previous Sound"-ra
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Lásd még

* Osztály [Effect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)