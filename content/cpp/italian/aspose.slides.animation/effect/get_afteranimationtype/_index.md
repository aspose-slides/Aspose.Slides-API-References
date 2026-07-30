---
title: get_AfterAnimationType()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un tipo di animazione successiva per l'effetto. Leggi AfterAnimationType.
type: docs
weight: 222
url: /it/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() metodo


Definisce un tipo di animazione successiva per l'effetto. Leggi [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifica l'animazione After dell'effetto in "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Vedi anche

* Enum [AfterAnimationType](../../afteranimationtype/)
* Classe [Effect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)