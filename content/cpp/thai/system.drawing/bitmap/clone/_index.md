---
title: Clone()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: สร้างสำเนาของอ็อบเจ็กต์ปัจจุบัน
type: docs
weight: 183
url: /th/system.drawing/bitmap/clone/
---
## Bitmap::Clone() เมธอด

สร้างสำเนาของอ็อบเจ็กต์ปัจจุบัน

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### ค่าที่ส่งกลับ

สำเนาของอ็อบเจ็กต์ปัจจุบัน

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) เมธอด

สร้างอ็อบเจ็กต์ [Bitmap](../) ที่เป็นตัวแทนสำเนาของส่วนของภาพบิตแมพที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่ระบุพื้นที่ที่จะคัดลอก |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | รูปแบบพิกเซลสำหรับ [Bitmap](../) ใหม่ |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [Bitmap](../) ที่สร้างขึ้น

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) เมธอด

สร้างอ็อบเจ็กต์ [Bitmap](../) ที่เป็นตัวแทนสำเนาของส่วนของภาพบิตแมพที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมที่ระบุพื้นที่ที่จะคัดลอก |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | รูปแบบพิกเซลสำหรับ [Bitmap](../) ใหม่ |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [Bitmap](../) ที่สร้างขึ้น

## ดูเพิ่มเติม

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Image](../../image/)
* คลาส [Bitmap](../)
* คลาส [Rectangle](../../rectangle/)
* คลาส [RectangleF](../../rectanglef/)
* เนมสเปซ [System::Drawing](../../)
* Library [Aspose.Slides](../../../)