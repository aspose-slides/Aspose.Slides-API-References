---
title: set_AfterAnimationType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen Nach-Animationstyp für den Effekt. Schreiben Sie AfterAnimationType.
type: docs
weight: 235
url: /de/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) method


Definiert einen Nach-Animationstyp für den Effekt. Schreiben Sie [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt den ersten Effekt der ersten Folie.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändert die Nach-Animation des Effekts zu "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Siehe auch

* Aufzählung [AfterAnimationType](../../afteranimationtype/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)