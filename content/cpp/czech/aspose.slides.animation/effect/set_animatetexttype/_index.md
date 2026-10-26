---
title: set_AnimateTextType()
second_title: Aspose.Slides pro C++ API Reference
description: Definuje typ animovaného textu pro efekt. Text tvaru může být animován po písmenu, po slově nebo najednou. Zapište AnimateTextType.
type: docs
weight: 287
url: /cs/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) method


Definuje typ animovaného textu pro efekt. Text tvaru může být animován po písmenu, po slově nebo najednou. Zapište [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt prvního snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní typ animovaného textu efektu na "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Viz také

* Výčet [AnimateTextType](../../animatetexttype/)
* Třída [Effect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)