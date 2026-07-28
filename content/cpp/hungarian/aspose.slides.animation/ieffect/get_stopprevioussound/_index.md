---
title: get_StopPreviousSound()
second_title: Aspose.Slides C++ API-referencia
description: Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasás bool.
type: docs
weight: 196
url: /hu/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() metódus


Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dia első effektusát kérdezzük le.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// A második dia első effektusát kérdezzük le.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // A második effektus Enhancements/Sound beállítása "Stop Previous Sound" értékre
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Lásd még

* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)