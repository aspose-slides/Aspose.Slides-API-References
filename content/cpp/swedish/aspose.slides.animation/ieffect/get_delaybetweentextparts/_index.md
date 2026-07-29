---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentsatsen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs float.
type: docs
weight: 300
url: /sv/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() metod

Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentsatsen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Anmärkningar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra effektens Animate text-typ till "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Ställ in fördröjningen mellan animerade textdelar till 20% av effektens varaktighet.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Se även

* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)