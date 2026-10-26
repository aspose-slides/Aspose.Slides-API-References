---
title: set_AfterAnimationType()
second_title: Riferimento API Aspose.Slides per C++
description: Definito un tipo di animazione successiva per l'effetto. Scrivi AfterAnimationType.
type: docs
weight: 235
url: /it/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metodo


Definito un tipo di animazione successiva per l'effetto. Scrivi [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifica l'animazione successiva dell'effetto in "Nascondi al prossimo clic del mouse"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Vedi anche

* Enum [AfterAnimationType](../../afteranimationtype/)
* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)