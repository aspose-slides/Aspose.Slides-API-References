---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentandelen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Skriv **float**.
type: docs
weight: 313
url: /sv/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) metod


Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger andelen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Skriv **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra effekttypen för animerad text till "Per ord"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Ställ in fördröjningen mellan animerade textdelar till 20% av effektens varaktighet.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Se även

* Klass [Effect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)