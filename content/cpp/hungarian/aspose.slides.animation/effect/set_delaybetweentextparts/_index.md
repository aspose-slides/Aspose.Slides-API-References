---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatároz egy késleltetést az animált szövegrészek (szavak vagy betűk) között. Egy pozitív érték a hatás időtartamának százalékát adja meg. Egy negatív érték a késleltetést másodpercben adja meg. Írja float.
type: docs
weight: 313
url: /hu/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) metódus

Meghatároz egy késleltetést az animált szövegrészek (szavak vagy betűk) között. Egy pozitív érték a hatás időtartamának százalékát adja meg. Egy negatív érték a késleltetést másodpercben adja meg. Írja **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## Megjegyzés



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

* Osztály [Effect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)