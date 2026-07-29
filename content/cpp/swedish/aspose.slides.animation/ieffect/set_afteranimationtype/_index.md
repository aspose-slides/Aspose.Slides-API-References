---
title: set_AfterAnimationType()
second_title: Aspose.Slides för C++ API-referens
description: Definierade en efteranimationstyp för effekt. Skriv AfterAnimationType.
type: docs
weight: 235
url: /sv/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metod


Definierade en efteranimationstyp för effekt. Skriv [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra efteranimationen för effekten till "Dölj vid nästa musklick"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Se även

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)