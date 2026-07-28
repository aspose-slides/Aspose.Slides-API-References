---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Definiuje opóźnienie między animowanymi częściami tekstu (słowami lub literami). Wartość dodatnia określa procent czasu trwania efektu. Wartość ujemna określa opóźnienie w sekundach. Odczyt float.
type: docs
weight: 300
url: /pl/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() metoda

Definiuje opóźnienie między animowanymi częściami tekstu (słowami lub literami). Wartość dodatnia określa procent czasu trwania efektu. Wartość ujemna określa opóźnienie w sekundach. Odczyt **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
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

## Zobacz także

* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)