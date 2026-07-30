---
title: get_AnimateTextType()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Definuje typ animovaného textu pro efekt. Text ve tvaru může být animován po písmenu, po slově nebo najednou. Přečtěte si AnimateTextType.
type: docs
weight: 274
url: /cs/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() metoda


Definuje typ animovaného textu pro efekt. Text ve tvaru může být animován po písmenech, po slovech nebo najednou. Přečtěte si [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
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

* Výčtový typ [AnimateTextType](../../animatetexttype/)
* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)