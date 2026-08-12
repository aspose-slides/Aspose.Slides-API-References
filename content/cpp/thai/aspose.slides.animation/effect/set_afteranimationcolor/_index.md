---
title: set_AfterAnimationColor()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดสีหลังการเคลื่อนไหวสำหรับเอฟเฟกต์ เขียน IColorFormat.
type: docs
weight: 261
url: /th/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) เมธอด


กำหนดสีหลังการเคลื่อนไหวสำหรับเอฟเฟกต์ เขียน [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## ดูเพิ่มเติม

* ประเภทกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [IColorFormat](../../../aspose.slides/icolorformat/)
* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)