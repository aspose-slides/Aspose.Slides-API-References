---
title: get_DelayBetweenTextParts()
second_title: Riferimento API Aspose.Slides per C++
description: Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell'effetto. Un valore negativo specifica il ritardo in secondi. Leggi float.
type: docs
weight: 300
url: /it/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() metodo


Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell’effetto. Un valore negativo specifica il ritardo in secondi. Leggi **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
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

* Classe [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)