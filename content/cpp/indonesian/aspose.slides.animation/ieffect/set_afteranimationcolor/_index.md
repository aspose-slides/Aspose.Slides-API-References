---
title: set_AfterAnimationColor()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan warna setelah animasi untuk efek. Tulis IColorFormat.
type: docs
weight: 261
url: /id/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metode

Mendefinisikan warna setelah animasi untuk efek. Tulis [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## Keterangan

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
* RuangNama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)