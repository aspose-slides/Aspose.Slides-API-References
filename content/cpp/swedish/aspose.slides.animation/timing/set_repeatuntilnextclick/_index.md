---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides för C++ API-referens
description: Det här attributet anger om effekten ska upprepas tills nästa klick. Skriv bool.
type: docs
weight: 170
url: /sv/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) metod


Det här attributet anger om effekten ska upprepas tills nästa klick. Skriv **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Se även

* Klass [Timing](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)