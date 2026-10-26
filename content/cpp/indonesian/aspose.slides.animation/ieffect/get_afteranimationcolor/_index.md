---
title: get_AfterAnimationColor()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan warna setelah animasi untuk efek. Baca IColorFormat.
type: docs
weight: 248
url: /id/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() metode

Mendefinisikan warna setelah animasi untuk efek. Baca [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## Catatan

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IColorFormat](../../../aspose.slides/icolorformat/)
* Kelas [IEffect](../)
* Ruang nama [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)