---
title: set_AnimateShapes()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าตัวเลือกการเคลื่อนไหวของรูปร่าง เขียน bool.
type: docs
weight: 40
url: /th/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) เมธอด


ตั้งค่าตัวเลือกการเคลื่อนไหวของรูปร่าง เขียน **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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

* คลาส [Html5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)