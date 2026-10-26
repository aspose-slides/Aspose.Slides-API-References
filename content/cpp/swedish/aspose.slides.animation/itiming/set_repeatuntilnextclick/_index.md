---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om effekten ska upprepas tills nästa klick. Skriv bool.
type: docs
weight: 170
url: /sv/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) metod


Detta attribut anger om effekten ska upprepas tills nästa klick. Skriv **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Hämtar effektsekvensen för den första bilden
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Hämtar den första effekten i huvudsekvensen.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Ändrar effektens Timing/Repeat till "Till slutet av bilden"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Se också

* Klass [ITiming](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)