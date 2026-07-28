---
title: get_AfterAnimationType()
second_title: Aspose.Slides C++ API referencia
description: Meghatároz egy animáció utáni típust a hatáshoz. Olvassa el AfterAnimationType.
type: docs
weight: 222
url: /hu/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() metódus


Meghatároz egy animáció utáni típust a hatáshoz. Olvassa el [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dia első effektusát lekérdezi.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// A hatás animáció után típusát "Hide on Next Mouse Click"-re változtatja
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lásd még

* Enum [AfterAnimationType](../../afteranimationtype/)
* Osztály [Effect](../)
* Névterület [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)