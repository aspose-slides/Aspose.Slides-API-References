---
title: get_AfterAnimationType()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatározza az effektus után animáció típusát. Olvassa el az AfterAnimationType.
type: docs
weight: 222
url: /hu/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() metódus


Meghatározza az effektus után animáció típusát. Olvassa el [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dián az első effektus lekérése.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Az effektus után animáció beállítása "Hide on Next Mouse Click" értékre
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lásd még

* Enum [AfterAnimationType](../../afteranimationtype/)
* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)