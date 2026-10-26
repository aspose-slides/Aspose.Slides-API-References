---
title: set_AnimateTextType()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Scrivi AnimateTextType.
type: docs
weight: 287
url: /it/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metodo


Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Scrivi [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambia il tipo di animazione del testo dell'effetto in "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Vedi anche

* Enum [AnimateTextType](../../animatetexttype/)
* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)