---
title: set_AfterAnimationColor()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zdefiniowano kolor po animacji dla efektu. Użyj IColorFormat.
type: docs
weight: 261
url: /pl/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metoda

Zdefiniowano kolor po animacji dla efektu. Napisz [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
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