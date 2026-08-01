---
title: set_AfterAnimationType()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een after-animatietype voor effect. Schrijf AfterAnimationType.
type: docs
weight: 235
url: /nl/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) methode

Definieert een after-animatietype voor effect. Schrijf [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Opmerkingen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Wijzig de After-animatie van het effect naar "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Zie Ook

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klasse [Effect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)