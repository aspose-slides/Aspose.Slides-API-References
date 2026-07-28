---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides dla C++ – referencja API
description: Ten atrybut określa, czy efekt będzie powtarzany aż do następnego kliknięcia. Odczyt **bool**.
type: docs
weight: 157
url: /pl/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() metoda


Ten atrybut określa, czy efekt będzie powtarzany aż do następnego kliknięcia. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Pobiera sekwencję efektów dla pierwszego slajdu
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Pobiera pierwszy efekt głównej sekwencji.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Zmienia Timing/Repeat efektu na "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Zobacz także

* Klasa [ITiming](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)