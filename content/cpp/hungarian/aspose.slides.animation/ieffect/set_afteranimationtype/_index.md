---
title: set_AfterAnimationType()
second_title: Aspose.Slides C++ API referencia
description: Definiálja az effektus után animáció típusát. Írja AfterAnimationType.
type: docs
weight: 235
url: /hu/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metódus


Az effektus után animáció típusát definiálja. Írja [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dia első effektusát lekérjük.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Az AfterAnimationType értékét módosítja a "Hide on Next Mouse Click"-ra
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lásd még

* Enum [AfterAnimationType](../../afteranimationtype/)
* Osztály [IEffect](../)
* Névterület [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)