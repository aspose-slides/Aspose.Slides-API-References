---
title: Subtract()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบค่าความกว้างและความสูงของอ็อบเจกต์ SizeF ที่ระบุออกจากค่าพิกัด X และ Y ของอ็อบเจกต์ PointF ที่ระบุตามลำดับ
type: docs
weight: 157
url: /th/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) เมธอด

ลบค่าความกว้างและความสูงของอ็อบเจกต์ [SizeF](../../sizef/) ที่ระบุออกจากค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](../) ที่ระบุตามลำดับ

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point | const [PointF](../)\& | จุด point เพื่อแปล |
| size | const [SizeF](../../sizef/)\& | อ็อบเจกต์ [SizeF](../../sizef/) ที่ระบุค่าที่จะลบจากค่าพิกัดของ **point** |

### Return Value

อ็อบเจกต์ [PointF](../) ใหม่ที่ค่าพิกัด X เท่ากับผลลัพธ์ของการลบค่าความกว้างของ **size** จากค่าพิกัด X ของ **point** และค่าพิกัด Y เท่ากับผลลัพธ์ของการลบค่าความสูงของ **size** จากค่าพิกัด Y ของ **point**

## PointF::Subtract(const PointF\&, const Size\&) เมธอด

ลบค่าความกว้างและความสูงของอ็อบเจกต์ [Size](../../size/) ที่ระบุออกจากค่าพิกัด X และ Y ของอ็อบเจกต์ [PointF](../) ที่ระบุตามลำดับ

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| point | const [PointF](../)\& | จุด point เพื่อแปล |
| size | const [Size](../../size/)\& | อ็อบเจกต์ [Size](../../size/) ที่ระบุค่าที่จะลบจากค่าพิกัดของ **point** |

### Return Value

อ็อบเจกต์ [PointF](../) ใหม่ที่ค่าพิกัด X เท่ากับผลลัพธ์ของการลบค่าความกว้างของ **size** จากค่าพิกัด X ของ **point** และค่าพิกัด Y เท่ากับผลลัพธ์ของการลบค่าความสูงของ **size** จากค่าพิกัด Y ของ **point**

## ดูเพิ่มเติม

* คลาส [PointF](../)
* คลาส [SizeF](../../sizef/)
* คลาส [Size](../../size/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)