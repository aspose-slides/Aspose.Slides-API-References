---
title: FromStream()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ Image จากสตรีมที่ระบุ.
type: docs
weight: 339
url: /th/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) เมธอด

สร้างอ็อบเจ็กต์ [Image](../) จากสตรีมที่ระบุ.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูลภาพ |
| use_embedded_color_management | **bool** | ละเว้น |
| validate_image_data | **bool** | ละเว้น |

### ค่าที่ส่งคืน

ตัวชี้ shared pointer ไปยังอ็อบเจ็กต์ [Image](../) ที่สร้าง.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Image](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)