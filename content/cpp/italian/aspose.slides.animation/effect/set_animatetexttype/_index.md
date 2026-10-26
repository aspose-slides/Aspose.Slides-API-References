---
title: set_AnimateTextType()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Scrivi AnimateTextType.
type: docs
weight: 287
url: /it/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metodo


Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Scrivi [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Vedi anche

* Enum [AnimateTextType](../../animatetexttype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)