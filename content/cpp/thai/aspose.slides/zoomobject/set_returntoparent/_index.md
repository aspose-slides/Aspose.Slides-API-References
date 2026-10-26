---
title: set_ReturnToParent()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "กำหนดพฤติกรรมการนำทางในสไลด์โชว์. เขียน bool. ค่าเริ่มต้น: false"
type: docs
weight: 40
url: /th/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) เมธอด


กำหนดพฤติกรรมการนำทางในสไลด์โชว์. เขียน **bool**. ค่าเริ่มต้น: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## หมายเหตุ


ค่าจริงของคุณสมบัติกำหนดพฤติกรรมการคืนสู่พาเรนท์ในการนำทางในสไลด์โชว์. 

ตัวอย่าง: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## ดูเพิ่มเติม

* คลาส [ZoomObject](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)