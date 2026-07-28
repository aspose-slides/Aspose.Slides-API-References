---
title: get_DelayBetweenTextParts()
second_title: Referencja API Aspose.Slides dla C++
description: Definiuje opóźnienie między animowanymi częściami tekstu (słowa lub litery). Dodatnia wartość określa procent czasu trwania efektu. Ujemna wartość określa opóźnienie w sekundach. Odczyt float.
type: docs
weight: 300
url: /pl/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() metoda

Definiuje opóźnienie między animowanymi częściami tekstu (słowa lub litery). Dodatnia wartość określa procent czasu trwania efektu. Ujemna wartość określa opóźnienie w sekundach. Zwraca **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Zobacz również

* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)