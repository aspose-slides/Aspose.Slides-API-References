---
title: set_AnimateTextType()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Definuje typ animovaného textu pro efekt. Text tvaru může být animován po písmenu, po slově nebo najednou. Zapište AnimateTextType.
type: docs
weight: 287
url: /cs/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) metoda


Definuje typ animovaného textu pro efekt. Text tvaru může být animován po písmenu, po slově nebo najednou. Zapište [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt z první snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní typ animovaného textu efektu na "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Viz také

* Enum [AnimateTextType](../../animatetexttype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)