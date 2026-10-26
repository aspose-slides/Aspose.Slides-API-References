---
title: set_ReturnToParent()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "กำหนดพฤติกรรมการนำทางในสไลด์โชว์. เขียน bool. ค่าเริ่มต้น: false"
type: docs
weight: 40
url: /th/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) เมธอด


กำหนดพฤติกรรมการนำทางในสไลด์โชว์. เขียน **bool**. ค่าเริ่มต้น: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## หมายเหตุ


ค่าจริงของคุณสมบัติกำหนดพฤติกรรมการกลับไปยังพาเรนท์ในสไลด์โชว์.

ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## ดูเพิ่มเติม

* คลาส [IZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)