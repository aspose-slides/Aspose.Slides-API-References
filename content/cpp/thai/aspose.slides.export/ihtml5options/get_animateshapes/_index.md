---
title: get_AnimateShapes()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนตัวเลือกการเคลื่อนไหวของรูปร่าง อ่าน bool.
type: docs
weight: 27
url: /th/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() เมธอด

ส่งคืนตัวเลือกการเคลื่อนไหวของรูปร่าง อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
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
* เนมส페ซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)