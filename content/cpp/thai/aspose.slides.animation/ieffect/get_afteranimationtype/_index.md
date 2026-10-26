---
title: get_AfterAnimationType()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดประเภทการแอนิเมชันหลังสำหรับเอฟเฟกต์. อ่าน AfterAnimationType.
type: docs
weight: 222
url: /th/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() เมธอด


กำหนดประเภทการแอนิเมชันหลังจากเอฟเฟกต์. อ่าน [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับเอฟเฟ็กต์แรกของสไลด์แรก.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// เปลี่ยนเอฟเฟ็กต์ After animation เป็น "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## ดูเพิ่มเติม

* Enum [AfterAnimationType](../../afteranimationtype/)
* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)