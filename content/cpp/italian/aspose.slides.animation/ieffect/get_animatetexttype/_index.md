---
title: get_AnimateTextType()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un tipo di testo animato per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Leggi AnimateTextType.
type: docs
weight: 274
url: /it/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() metodo

Definisce un tipo di testo animato per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Leggi [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambia il tipo di testo animato dell'effetto in "Per lettera"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Vedi anche

* Enum [AnimateTextType](../../animatetexttype/)
* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)