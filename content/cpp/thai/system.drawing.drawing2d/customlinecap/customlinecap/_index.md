---
title: CustomLineCap()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: สร้างอินสแตนซ์ใหม่ของคลาส CustomLineCap ซึ่งแสดงถึงหัวเส้นที่กำหนดโดยผู้ใช้ด้วยคุณสมบัติที่ระบุ
type: docs
weight: 1
url: /th/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [CustomLineCap](../) ซึ่งแสดงถึงหัวเส้นที่กำหนดโดยผู้ใช้ด้วยคุณสมบัติที่ระบุ

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | ระบุการเติมสำหรับหัวเส้นแบบกำหนดเอง |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | ระบุโครงร่างของหัวเส้นแบบกำหนดเอง |
| baseCap | [LineCap](../../linecap/) | หัวเส้นฐานที่ใช้สร้างหัวเส้นแบบกำหนดเอง |
| baseInset | **float** | ระบุระยะทางระหว่างเส้นและหัวเส้น |

## ดูเพิ่มเติม

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [GraphicsPath](../../graphicspath/)
* คลาส [CustomLineCap](../)
* เนมสเปซ [System::Drawing::Drawing2D](../../)
* ไลบรารี [Aspose.Slides](../../../)