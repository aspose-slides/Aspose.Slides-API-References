---
title: get_AfterAnimationType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen Nachanimationstyp für den Effekt. Lesen Sie AfterAnimationType.
type: docs
weight: 222
url: /de/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() Methode

Definiert einen Nachanimationstyp für den Effekt. Lesen Sie [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Anmerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändert die Nachanimation des Effekts zu "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Siehe auch

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)