---
title: GetTile()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างภาพไทล์สำหรับการเติมลายด้วยสีที่ระบุ
type: docs
weight: 53
url: /th/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) เมธอด

สร้างภาพไทล์สำหรับการเติมลายด้วยสีที่ระบุ.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | พื้นหลัง [System::Drawing::Color](../../../system.drawing/color/) สำหรับลาย |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | พื้นหน้า [System::Drawing::Color](../../../system.drawing/color/) สำหรับลาย |

### ค่าที่ส่งกลับ

Tile [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) เมธอด

สร้างภาพไทล์สำหรับการเติมลาย.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | ค่าเริ่มต้น [System::Drawing::Color](../../../system.drawing/color/) |

### ค่าที่ส่งกลับ

Tile [IImage](../../iimage/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../iimage/)
* คลาส [Color](../../../system.drawing/color/)
* คลาส [PatternFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)