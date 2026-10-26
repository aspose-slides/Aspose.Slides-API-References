---
title: set_AfterAnimationType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟกต์ เขียน AfterAnimationType.
type: docs
weight: 235
url: /th/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) เมธอด

กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟคต์ เขียน [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## หมายเหตุ

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// ดึงเอฟเฟกต์แรกของสไลด์แรก.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// เปลี่ยนเอฟเฟกต์ After animation เป็น "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## ดูเพิ่มเติม

* Enum [AfterAnimationType](../../afteranimationtype/)
* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)