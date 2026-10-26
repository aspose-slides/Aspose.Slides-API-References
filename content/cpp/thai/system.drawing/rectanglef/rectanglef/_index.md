---
title: RectangleF()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ RectangleF ที่แสดงสี่เหลี่ยมโดยมีพิกัด X และ Y และค่าความกว้างและความสูงตั้งเป็น 0.
type: docs
weight: 1
url: /th/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](../) ที่แสดงสี่เหลี่ยมที่มีพิกัด X และ Y และค่า width และ height ถูกตั้งเป็น 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](../) ที่แสดงสี่เหลี่ยมโดยมีพิกัดของมุมบนซ้ายที่ระบุและค่า width และ height

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | ค่าของพิกัด X ของมุมบนซ้ายของสี่เหลี่ยม |
| y | **float** | ค่ของพิกัด Y ของมุมบนซ้ายของสี่เหลี่ยม |
| width | **float** | ค่าของ width ของสี่เหลี่ยม |
| height | **float** | ค่าของ height ของสี่เหลี่ยม |

## RectangleF::RectangleF(const PointF&, const SizeF&) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](../) ที่แสดงสี่เหลี่ยมโดยมีพิกัดของมุมบนซ้ายที่ระบุเป็นอินสแตนซ์ของคลาส [PointF](../../pointf/) และ width และ height เป็นอินสแตนซ์ของคลาส [SizeF](../../sizef/)

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | ระบุตำแหน่งของมุมบนซ้ายของสี่เหลี่ยม |
| size | const [SizeF](../../sizef/)\& | ระบุ width และ height ของสี่เหลี่ยม |

## RectangleF::RectangleF(const Rectangle&) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [RectangleF](../) ที่แสดงสี่เหลี่ยมที่เทียบเท่ากับสี่เหลี่ยมที่ระบุ

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | อินสแตนซ์ของคลาส [Rectangle](../../rectangle/) ที่ระบุตำแหน่งและขนาดของสี่เหลี่ยมที่วัตถุจะเป็นตัวแทน |

## ดูเพิ่มเติม

* คลาส [RectangleF](../)
* คลาส [PointF](../../pointf/)
* คลาส [SizeF](../../sizef/)
* คลาส [Rectangle](../../rectangle/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)