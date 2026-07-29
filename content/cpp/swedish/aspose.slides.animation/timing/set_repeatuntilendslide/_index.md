---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut specificerar om effekten ska upprepas tills slutet av bilden. Skriv bool.
type: docs
weight: 144
url: /sv/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) metod


Det här attributet specificerar om effekten kommer att upprepas tills slutet av bilden. Skriv **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Hämtar effektsekvensen för den första bilden
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Hämtar den första effekten i huvudsekvensen.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Ändrar effektens Timing/Repeat till "Till bildens slut"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Se även

* Klass [Timing](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)