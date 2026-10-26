---
title: get_AfterAnimationType()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en efteranimationstyp för effekt. Läs AfterAnimationType.
type: docs
weight: 222
url: /sv/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() metod

Definierar en efteranimationstyp för effekt. Läs [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Se även

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klass [Effect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)