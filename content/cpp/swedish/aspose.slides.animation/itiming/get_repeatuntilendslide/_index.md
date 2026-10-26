---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om effekten ska upprepas tills slutet av bilden. Läs bool.
type: docs
weight: 131
url: /sv/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() metod

Detta attribut anger om effekten ska upprepas tills slutet av bilden. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Anmärkningar

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Hämtar effektsekvensen för den första bilden
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Hämtar den första effekten i huvudsekvensen.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Ändrar effektens Timing/Upprepning till "Till slutet av bilden"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Se även

* Klass [ITiming](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)