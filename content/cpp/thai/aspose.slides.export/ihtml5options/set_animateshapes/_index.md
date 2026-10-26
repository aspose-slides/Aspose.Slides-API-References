---
title: set_AnimateShapes()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตั้งค่าตัวเลือกการเคลื่อนไหวของรูปทรง. เขียน bool.
type: docs
weight: 40
url: /th/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) เมธอด

ตั้งค่าตัวเลือกการเคลื่อนไหวของรูปทรง. เขียน **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```

## ดูเพิ่มเติม

* คลาส [IHtml5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)