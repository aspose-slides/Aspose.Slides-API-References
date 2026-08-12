---
title: get_AnimateTransitions()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: คืนค่าตัวเลือกการทำแอนิเมชันการเปลี่ยนแปลง. อ่าน bool.
type: docs
weight: 1
url: /th/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() เมธอด

คืนค่าตัวเลือกการทำแอนิเมชันการเปลี่ยนแปลง. อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
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

* คลาส [IHtml5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)