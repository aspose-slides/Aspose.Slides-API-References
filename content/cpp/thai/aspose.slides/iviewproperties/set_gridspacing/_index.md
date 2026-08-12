---
title: set_GridSpacing()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดระยะห่างของกริดที่ควรใช้สำหรับกริดที่สนับสนุนเอกสารการนำเสนอ โดยหน่วยเป็นพอยต์ เขียนเป็น float.
type: docs
weight: 105
url: /th/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) เมธอด


กำหนดระยะห่างของกริดที่ควรใช้สำหรับกริดที่สนับสนุนเอกสารการนำเสนอ โดยหน่วยเป็นพอยต์ เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## หมายเหตุ


ค่าระยะห่างของกริดต้องเป็นจำนวนบวก ช่วงค่าที่ทั่วไปอยู่ตั้งแต่ 1 มม. (2.8349607 พอยต์) ถึง 2 นิ้ว (144 พอยต์). 

โค้ดตัวอย่างต่อไปนี้แสดงวิธีเปลี่ยนระยะห่างของกริดในงานนำเสนอ PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IViewProperties](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)