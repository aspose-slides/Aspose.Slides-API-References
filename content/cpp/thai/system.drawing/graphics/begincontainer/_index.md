---
title: BeginContainer()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: บันทึกคอนเทนเนอร์พร้อมสถานะปัจจุบันของอ็อบเจกต์นี้, เปิดและใช้คอนเทนเนอร์ใหม่ และคืนค่าคอนเทนเนอร์ที่บันทึกไว้.
type: docs
weight: 976
url: /th/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() เมธอด

บันทึกคอนเทนเนอร์พร้อมสถานะปัจจุบันของอ็อบเจกต์นี้, เปิดและใช้คอนเทนเนอร์ใหม่ และคืนค่าคอนเทนเนอร์ที่บันทึกไว้.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) เมธอด

บันทึกคอนเทนเนอร์พร้อมสถานะปัจจุบันของอ็อบเจกต์นี้, เปิดและใช้คอนเทนเนอร์ใหม่ และคืนค่าคอนเทนเนอร์ที่บันทึกไว้.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่ระบุการแปลงสเกลของคอนเทนเนอร์ใหม่ ใช้ร่วมกับ **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่ระบุการแปลงสเกลของคอนเทนเนอร์ใหม่ ใช้ร่วมกับ **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | ค่าที่ระบุหน่วยวัดของคอนเทนเนอร์ใหม่ |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) เมธอด

บันทึกคอนเทนเนอร์พร้อมสถานะปัจจุบันของอ็อบเจกต์นี้, เปิดและใช้คอนเทนเนอร์ใหม่ และคืนค่าคอนเทนเนอร์ที่บันทึกไว้.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมที่ระบุการแปลงสเกลของคอนเทนเนอร์ใหม่ ใช้ร่วมกับ **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมที่ระบุการแปลงสเกลของคอนเทนเนอร์ใหม่ ใช้ร่วมกับ **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | ค่าที่ระบุหน่วยวัดของคอนเทนเนอร์ใหม่ |

## ดูเพิ่มเติม

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)