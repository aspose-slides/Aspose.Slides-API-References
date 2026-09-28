---
title: GetTile()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: สร้างภาพไทล์สำหรับการเติมลายแบบด้วยสีที่ระบุ.
type: docs
weight: 53
url: /th/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) เมธอด

สร้างภาพไทล์สำหรับการเติมลายด้วยสีที่ระบุ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | พื้นหลัง [System::Drawing::Color](../../../system.drawing/color/) สำหรับลายแบบ. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | พื้นหน้า [System::Drawing::Color](../../../system.drawing/color/) สำหรับลายแบบ. |

### ค่าที่ส่งคืน

ไทล์ [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) เมธอด

สร้างภาพไทล์สำหรับการเติมลายแบบ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | ค่าเริ่มต้น [System::Drawing::Color](../../../system.drawing/color/) ที่กำหนดในอ็อบเจกต์ StyleEx ของ ShapeEx. สีของ Fill อาจขึ้นกับค่านี้. |

### ค่าที่ส่งคืน

ไทล์ [IImage](../../iimage/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../iimage/)
* คลาส [Color](../../../system.drawing/color/)
* คลาส [IPatternFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)