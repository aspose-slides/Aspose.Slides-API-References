---
title: get_ReturnToParent()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "รับพฤติกรรมการนำทางในสไลด์โชว์. อ่าน bool. ค่าเริ่มต้น: false"
type: docs
weight: 27
url: /th/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() เมธอด


รับค่าพฤติกรรมการนำทางในสไลด์โชว์. อ่าน **bool**. ค่าเริ่มต้น: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## หมายเหตุ


ค่าจริงของคุณสมบัตินี้ระบุพฤติกรรมการกลับไปยังพาเรนต์ในสไลด์โชว์. 

ตัวอย่าง: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## ดูเพิ่มเติม

* คลาส [ZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)