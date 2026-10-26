---
title: set_AfterAnimationColor()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Definuje barvu po animaci pro efekt. Zapište IColorFormat.
type: docs
weight: 261
url: /cs/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metoda

Definuje barvu po animaci pro efekt. Zapište [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IColorFormat](../../../aspose.slides/icolorformat/)
* třída [Effect](../)
* jmenný prostor [Aspose::Slides::Animation](../../)
* knihovna [Aspose.Slides](../../../)