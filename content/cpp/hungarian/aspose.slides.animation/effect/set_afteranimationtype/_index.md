---
title: set_AfterAnimationType()
second_title: Aspose.Slides C++ API Referencia
description: Meghatároz egy utóanimáció típust az effektushoz. Írja be AfterAnimationType.
type: docs
weight: 235
url: /hu/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metódus

Meghatároz egy utóanimáció típust az effektushoz. Írja be [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Megjegyzések

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lásd még

* Enum [AfterAnimationType](../../afteranimationtype/)
* Osztály [Effect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)