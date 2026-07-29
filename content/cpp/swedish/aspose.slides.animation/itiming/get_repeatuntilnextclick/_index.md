---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut specificerar om effekten ska upprepas tills nästa klick. Läs bool.
type: docs
weight: 157
url: /sv/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() metod


Detta attribut specificerar om effekten upprepas tills nästa klick. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
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

* Klass [ITiming](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)