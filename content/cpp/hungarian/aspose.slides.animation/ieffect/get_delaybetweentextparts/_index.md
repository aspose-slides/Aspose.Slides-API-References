---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides C++ API referencia
description: Meghatároz egy késleltetést az animált szövegrészek (szavak vagy betűk) között. Egy pozitív érték a hatás időtartamának százalékát adja meg. Egy negatív érték a késleltetést másodpercben adja meg. Olvassa float.
type: docs
weight: 300
url: /hu/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() metódus


Meghatároz egy késleltetést az animált szövegrészek (szavak vagy betűk) között. Egy pozitív érték a hatás időtartamának százalékát adja meg. Egy negatív érték a késleltetést másodpercben adja meg. Olvassa **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Lásd még

* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)