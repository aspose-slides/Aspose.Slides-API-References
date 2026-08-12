---
title: get_AfterAnimationColor()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดสีหลังการเคลื่อนไหวสำหรับเอฟเฟกต์. อ่าน IColorFormat.
type: docs
weight: 248
url: /th/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() เมธอด


กำหนดสีหลังการเคลื่อนไหวสำหรับเอฟเฟกต์. อ่าน [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IColorFormat](../../../aspose.slides/icolorformat/)
* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)