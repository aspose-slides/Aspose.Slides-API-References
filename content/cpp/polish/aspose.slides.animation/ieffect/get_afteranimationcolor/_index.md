---
title: get_AfterAnimationColor()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zdefiniowano kolor po animacji dla efektu. Przeczytaj IColorFormat.
type: docs
weight: 248
url: /pl/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() method


Zdefiniowano kolor po animacji dla efektu. Przeczytaj [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IColorFormat](../../../aspose.slides/icolorformat/)
* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)