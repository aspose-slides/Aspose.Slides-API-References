---
title: get_DelayBetweenTextParts()
second_title: Riferimento API Aspose.Slides per C++
description: Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo indica la percentuale della durata dell'effetto. Un valore negativo indica il ritardo in secondi. Leggi float.
type: docs
weight: 300
url: /it/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() metodo


Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo indica la percentuale della durata dell'effetto. Un valore negativo indica il ritardo in secondi. Leggi **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Vedi anche

* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)