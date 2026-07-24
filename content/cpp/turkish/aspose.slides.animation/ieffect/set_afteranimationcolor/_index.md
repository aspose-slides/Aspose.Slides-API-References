---
title: set_AfterAnimationColor()
second_title: Aspose.Slides için C++ API Referansı
description: Efekt için bir sonrasındaki animasyon rengini tanımladı. IColorFormat yazın.
type: docs
weight: 261
url: /tr/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metodu

Efekt için bir sonraki animasyon rengini tanımladı. [IColorFormat](../../../aspose.slides/icolorformat/) yazın.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## Açıklamalar

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IColorFormat](../../../aspose.slides/icolorformat/)
* Sınıf [IEffect](../)
* Ad Alanı [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)