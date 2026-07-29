---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut anger om effekten ska upprepas tills slutet av sliden. Skriv bool.
type: docs
weight: 144
url: /sv/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) metod


Detta attribut anger om effekten ska upprepas tills sliden är slut. Skriv **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Hämtar effektsekvensen för den första sliden
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Hämtar den första effekten i huvudsekvensen.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Ändrar effektens Timing/Repeat till "Till slutet av sliden"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Se också

* Klass [ITiming](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)