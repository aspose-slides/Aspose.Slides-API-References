---
title: get_AfterAnimationColor()
second_title: Aspose.Slides için C++ API Referansı
description: Efekt için bir son animasyon rengi tanımlanmıştır. IColorFormat'ı okuyun.
type: docs
weight: 248
url: /tr/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() metodu


Efekt için bir son animasyon rengi tanımlanmıştır. [IColorFormat](../../../aspose.slides/icolorformat/)'yi okuyun.

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
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
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)