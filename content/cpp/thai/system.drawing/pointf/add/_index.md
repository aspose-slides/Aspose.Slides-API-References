---
title: Add()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มค่าความกว้างและความสูงของอ็อบเจกต์ SizeF ที่ระบุไปยังค่าพิกัด X และ Y ของอ็อบเจกต์ PointF ที่ระบุโดยตรงตามลำดับ.
type: docs
weight: 144
url: /th/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) เมธอด

เพิ่มค่าความกว้างและความสูงของอ็อบเจกต์ [SizeF](../../sizef/) ที่ระบุไปยังค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](../) ที่ระบุโดยตรงตามลำดับ.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | const [PointF](../)\& | point ที่จะทำการแปลง |
| size | const [SizeF](../../sizef/)\& | อ็อบเจกต์ [SizeF](../../sizef/) ที่ระบุค่าที่จะเพิ่มไปยังค่าพิกัดของ **point** |

### ค่ารีเทิร์น

อ็อบเจกต์ [PointF](../) ใหม่ที่ค่าพิกัด X มีค่าเท่ากับผลบวกของค่าพิกัด X ของ **point** กับค่าความกว้างของ **size** และค่าพิกัด Y มีค่าเท่ากับผลบวกของค่าพิกัด Y ของ **point** กับค่าความสูงของ **size**

## PointF::Add(const PointF\&, const Size\&) เมธอด

เพิ่มค่าความกว้างและความสูงของอ็อบเจกต์ [Size](../../size/) ที่ระบุไปยังค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](../) ที่ระบุโดยตรงตามลำดับ.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | const [PointF](../)\& | point ที่จะทำการแปลง |
| size | const [Size](../../size/)\& | อ็อบเจกต์ [Size](../../size/) ที่ระบุค่าที่จะเพิ่มไปยังค่าพิกัดของ **point** |

### ค่ารีเทิร์น

อ็อบเจกต์ [PointF](../) ใหม่ที่ค่าพิกัด X มีค่าเท่ากับผลบวกของค่าพิกัด X ของ **point** กับค่าความกว้างของ **size** และค่าพิกัด Y มีค่าเท่ากับผลบวกของค่าพิกัด Y ของ **point** กับค่าความสูงของ **size**

## ดูเพิ่มเติม

* คลาส [PointF](../)
* คลาส [SizeF](../../sizef/)
* คลาส [Size](../../size/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)