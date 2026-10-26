---
title: get_AnimateTextType()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Leggi AnimateTextType.
type: docs
weight: 274
url: /it/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() metodo

Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Leggi [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Osservazioni

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifica il tipo di animazione del testo dell'effetto in "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Vedi anche

* Enum [AnimateTextType](../../animatetexttype/)
* Classe [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)