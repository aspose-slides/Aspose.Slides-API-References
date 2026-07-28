---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides C++ API Referenciája
description: Meghatározza a késleltetést az animált szövegrészek (szavak vagy betűk) között. A pozitív érték a hatás időtartamának százalékát adja meg. A negatív érték a késleltetést másodpercben adja meg. Írja float.
type: docs
weight: 313
url: /hu/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) metódus


Meghatározza a késleltetést az animált szövegrészek (szavak vagy betűk) között. A pozitív érték a hatás időtartamának százalékát adja meg. A negatív érték a késleltetést másodpercben adja meg. Írja **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
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