---
title: get_AfterAnimationType()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un tipo di animazione successiva per l'effetto. Leggi AfterAnimationType.
type: docs
weight: 222
url: /it/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() metodo

Definisce un tipo di animazione successiva per l'effetto. Leggi [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Osservazioni


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambia l'animazione successiva dell'effetto in "Nascondi al prossimo clic del mouse"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Vedi anche

* Enumerazione [AfterAnimationType](../../afteranimationtype/)
* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)