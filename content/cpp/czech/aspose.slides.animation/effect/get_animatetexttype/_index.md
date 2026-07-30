---
title: get_AnimateTextType()
second_title: Aspose.Slides pro C++ referenci API
description: Definuje typ animovaného textu pro efekt. Text tvaru může být animován po jednotlivých písmenech, po slovech nebo najednou. Přečtěte si AnimateTextType.
type: docs
weight: 274
url: /cs/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() metoda


Definuje typ animovaného textu pro efekt. Text tvaru může být animován po jednotlivých písmenech, po slovech nebo najednou. Přečtěte si [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
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