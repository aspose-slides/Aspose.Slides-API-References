---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een vertraging tussen geanimeerde tekstonderdelen (woorden of letters). Een positieve waarde geeft het percentage van de effectduur aan. Een negatieve waarde geeft de vertraging in seconden aan. Lees float.
type: docs
weight: 300
url: /nl/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() methode

Definieert een vertraging tussen geanimeerde tekstonderdelen (woorden of letters). Een positieve waarde geeft het percentage van de effectduur aan. Een negatieve waarde geeft de vertraging in seconden aan. Lees **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Opmerkingen


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Zie ook

* Klasse [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)