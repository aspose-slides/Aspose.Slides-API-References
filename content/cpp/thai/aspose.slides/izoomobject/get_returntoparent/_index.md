---
title: get_ReturnToParent()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ดึงพฤติกรรมการนำทางในสไลด์โชว์. อ่าน bool. ค่าเริ่มต้น: false"
type: docs
weight: 27
url: /th/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() เมธอด

ดึงพฤติกรรมการนำทางในสไลด์โชว์. อ่าน **bool**. ค่าเริ่มต้น: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## หมายเหตุ

ค่าจริงของคุณสมบัติกำหนดพฤติกรรมการคืนไปยังพาเรนต์ในสไลด์โชว์. 

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