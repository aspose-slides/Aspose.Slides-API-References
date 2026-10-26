---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides dla C++ - Referencja API
description: Ten atrybut określa, czy efekt będzie powtarzany aż do końca slajdu. Zapisz bool.
type: docs
weight: 144
url: /pl/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) metoda


Ten atrybut określa, czy efekt będzie powtarzany aż do końca slajdu. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Zobacz także

* Klasa [ITiming](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)