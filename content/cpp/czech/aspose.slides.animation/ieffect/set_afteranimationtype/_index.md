---
title: set_AfterAnimationType()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Definuje typ po animaci pro efekt. Zapište AfterAnimationType.
type: docs
weight: 235
url: /cs/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metoda

Definuje typ po animaci pro efekt. Zapište [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt první snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní After animation efekt na "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Viz také

* Enum [AfterAnimationType](../../afteranimationtype/)
* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)