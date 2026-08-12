---
title: GetTile()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างภาพไทล์สำหรับการเติมลายด้วยสีที่ระบุ
type: docs
weight: 53
url: /th/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) เมธอด

สร้างภาพไทล์สำหรับการเติมลายด้วยสีที่ระบุ

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | พื้นหลัง [System::Drawing::Color](../../../system.drawing/color/) สำหรับลาย |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | พื้นหน้า [System::Drawing::Color](../../../system.drawing/color/) สำหรับลาย |

### ค่าที่คืน

ไทล์ [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) เมธอด

สร้างภาพไทล์สำหรับการเติมลาย

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | ค่าเริ่มต้น [System::Drawing::Color](../../../system.drawing/color/) ที่กำหนดในออบเจ็กต์ StyleEx ของ ShapeEx. สีของการเติมอาจพึ่งพาค่านี้ |

### ค่าที่คืน

ไทล์ [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)