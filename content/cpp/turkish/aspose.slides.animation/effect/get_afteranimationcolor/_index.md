---
title: get_AfterAnimationColor()
second_title: Aspose.Slides for C++ API Referansı
description: Effect için bir sonraki animasyon rengini tanımlar. IColorFormat'ı okuyun.
type: docs
weight: 248
url: /tr/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() metodu

Effect için bir sonraki animasyon rengini tanımlar. [IColorFormat](../../../aspose.slides/icolorformat/)'yi okuyun.

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
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
* Sınıf [Effect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)