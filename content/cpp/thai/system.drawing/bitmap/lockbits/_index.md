---
title: LockBits()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ล็อก Bitmap ลงในหน่วยความจำของระบบ.
type: docs
weight: 118
url: /th/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle&, Imaging::ImageLockMode, Imaging::PixelFormat) เมธอด

ล็อก [Bitmap](../) ลงในหน่วยความจำของระบบ

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)& | สี่เหลี่ยมที่กำหนดบริเวณของภาพที่ต้องการล็อก |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | ระบุระดับการเข้าถึงของบิตแมพ |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | รูปแบบข้อมูลของบิตแมพนี้ |

### ค่าที่ส่งกลับ

ตัวชี้แบบ shared pointer ไปยังอ็อบเจ็กต์ BitmapData ที่บรรจุข้อมูลเกี่ยวกับการดำเนินการล็อกที่ทำไว้

## Bitmap::LockBits(const Rectangle&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr&) เมธอด

ล็อก [Bitmap](../) ลงในหน่วยความจำของระบบ

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)& | สี่เหลี่ยมที่กำหนดบริเวณของภาพที่ต้องการล็อก |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | ระบุระดับการเข้าถึงของบิตแมพ |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | รูปแบบข้อมูลของบิตแมพนี้ |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)& | บรรจุข้อมูลเกี่ยวกับการดำเนินการล็อก |

### ค่าที่ส่งกลับ

ตัวชี้แบบ shared pointer ไปยังอ็อบเจ็กต์ BitmapData ที่บรรจุข้อมูลเกี่ยวกับการดำเนินการล็อกที่ทำไว้

## ดูเพิ่มเติม

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)