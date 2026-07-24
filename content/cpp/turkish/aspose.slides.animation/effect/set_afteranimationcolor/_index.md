---
title: set_AfterAnimationColor()
second_title: Aspose.Slides için C++ API Referansı
description: Bir etki için bir sonraki animasyon rengini tanımlar. IColorFormat yazın.
type: docs
weight: 261
url: /tr/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metot

Bir etki için bir sonraki animasyon rengini tanımlar. Write [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
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