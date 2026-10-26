---
title: set_DelayBetweenTextParts()
second_title: Riferimento API Aspose.Slides per C++
description: Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell'effetto. Un valore negativo specifica il ritardo in secondi. Scrivi float.
type: docs
weight: 313
url: /it/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) metodo


Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell'effetto. Un valore negativo specifica il ritardo in secondi. Scrivi **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambia il tipo di animazione del testo dell'effetto in "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Imposta il ritardo tra le parti di testo animate al 20% della durata dell'effetto.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Vedi anche

* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)