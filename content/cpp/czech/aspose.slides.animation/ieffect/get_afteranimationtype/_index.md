---
title: get_AfterAnimationType()
second_title: Aspose.Slides pro C++ API referenci
description: Definuje typ animace po efektu. Přečtěte si AfterAnimationType.
type: docs
weight: 222
url: /cs/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() metoda


Definuje typ animace po efektu. Přečtěte si [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt první snímky.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní efekt After animation na "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Viz také

* Enum [AfterAnimationType](../../afteranimationtype/)
* Třída [IEffect](../)
* Obor názvů [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)