---
title: set_AfterAnimationColor()
second_title: Aspose.Slides for C++ API Reference
description: Defined an after animation color for effect. Write IColorFormat.
type: docs
weight: 261
url: /aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) method


Defined an after animation color for effect. Write [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorFormat](../../../aspose.slides/icolorformat/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)