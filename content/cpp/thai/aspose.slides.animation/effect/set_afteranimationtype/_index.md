---
title: set_AfterAnimationType()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟกต์ เขียน AfterAnimationType.
type: docs
weight: 235
url: /th/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) เมธอด


กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟกต์ เขียน [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับเอฟเฟกต์แรกของสไลด์แรก.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// เปลี่ยนการเคลื่อนไหวหลังของเอฟเฟกต์เป็น "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## ดูเพิ่มเติม

* enum [AfterAnimationType](../../afteranimationtype/)
* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)