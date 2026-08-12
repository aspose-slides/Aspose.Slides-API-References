---
title: set_AnimateTransitions()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าตัวเลือกการเคลื่อนไหวการเปลี่ยนผ่าน. เขียน bool.
type: docs
weight: 14
url: /th/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) เมธอด

ตั้งค่าตัวเลือกการแอนิเมชันการเปลี่ยนผ่าน. เขียน **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## ดูเพิ่มเติม

* คลาส [Html5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)