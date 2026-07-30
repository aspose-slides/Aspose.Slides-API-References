---
title: set_AfterAnimationType()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un tipo di animazione posteriore per l'effetto. Scrivi AfterAnimationType.
type: docs
weight: 235
url: /it/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metodo

Definisce un tipo di animazione posteriore per l'effetto. Scrivi [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambia l'animazione successiva dell'effetto in "HideOnNextMouseClick"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Vedi anche

* Enum [AfterAnimationType](../../afteranimationtype/)
* classe [Effect](../)
* namespace [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)