---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentsatsen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs float.
type: docs
weight: 300
url: /sv/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() metod

Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentsatsen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Se även

* Klass [Effect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)