---
title: set_StopPreviousSound()
second_title: Aspose.Slides C++ API referenciája
description: Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Írja bool.
type: docs
weight: 209
url: /hu/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) metódus


Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Írja **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dia első effektusát kérdezi le.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// A második dia első effektusát kérdezi le.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // A második effektus Enhancements/Sound beállítása "Stop Previous Sound"-ra
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Lásd még

* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)