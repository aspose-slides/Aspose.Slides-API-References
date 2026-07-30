---
title: get_AfterAnimationType()
second_title: Aspose.Slides pro C++ API Reference
description: Definuje typ následné animace pro efekt. Přečtěte si AfterAnimationType.
type: docs
weight: 222
url: /cs/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() metoda


Definuje typ následné animace pro efekt. Přečtěte si [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt prvního snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní efekt po animaci na "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Viz také

* Výčtový typ [AfterAnimationType](../../afteranimationtype/)
* Třída [Effect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)