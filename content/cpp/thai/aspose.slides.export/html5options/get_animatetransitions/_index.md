---
title: get_AnimateTransitions()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ส่งคืนตัวเลือกการทำแอนิเมชันของการเปลี่ยนภาพ. อ่าน bool.
type: docs
weight: 1
url: /th/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() เมธอด


คืนค่าตัวเลือกการทำแอนิเมชันของการเปลี่ยนภาพ. อ่าน **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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