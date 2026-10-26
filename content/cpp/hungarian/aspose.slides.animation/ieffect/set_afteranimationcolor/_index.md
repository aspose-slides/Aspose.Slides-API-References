---
title: set_AfterAnimationColor()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza az effektus utánjátszási színét. Írja be az IColorFormat-ot.
type: docs
weight: 261
url: /hu/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) módszer

Definiálja az effektus utánjátszási színét. Írja be a [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## Megjegyzések

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IColorFormat](../../../aspose.slides/icolorformat/)
* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)