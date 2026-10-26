---
title: set_AfterAnimationColor()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดสีหลังการแอนิเมชันสำหรับเอฟเฟกต์ เขียน IColorFormat.
type: docs
weight: 261
url: /th/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) เมธอด


กำหนดสีหลังการแอนิเมชันสำหรับเอฟเฟกต์ เขียน [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับเอฟเฟกต์แรกของสไลด์แรก.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// เปลี่ยนประเภท After animation ของเอฟเฟกต์เป็น "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// ตั้งค่าสี After animation ของเอฟเฟกต์.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IColorFormat](../../../aspose.slides/icolorformat/)
* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)