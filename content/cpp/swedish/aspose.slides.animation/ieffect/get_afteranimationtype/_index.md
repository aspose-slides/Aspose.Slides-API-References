---
title: get_AfterAnimationType()
second_title: Aspose.Slides för C++ API-referens
description: Definierade en efteranimations-typ för effekt. Läs AfterAnimationType.
type: docs
weight: 222
url: /sv/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() metod


Definierade en efteranimations-typ för effekt. Läs [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra effekten Efteranimation till "Dölj vid nästa musklick"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Se även

* Enum [AfterAnimationType](../../afteranimationtype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)