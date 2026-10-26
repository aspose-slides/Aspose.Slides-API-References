---
title: get_AfterAnimationColor()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζει ένα χρώμα μετά το animation για το εφέ. Διαβάστε IColorFormat.
type: docs
weight: 248
url: /el/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() μέθοδος


Ορίζει ένα χρώμα μετά το animation για το εφέ. Διαβάστε [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IColorFormat](../../../aspose.slides/icolorformat/)
* Κλάση [Effect](../)
* Ονομαχώρος [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)