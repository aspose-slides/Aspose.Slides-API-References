---
title: Subtract()
second_title: Aspose.Slides for C++ อ้างอิง API
description: ลบค่าความกว้างและความสูงของอ็อบเจ็กต์ Size ที่ระบุออกจากค่าพิกัด X และ Y ของอ็อบเจ็กต์ Point ที่ระบุโดยตรง
type: docs
weight: 196
url: /th/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) เมธอด

ลบค่าความกว้างและความสูงของอ็อบเจ็กต์ [Size](../../size/) ที่ระบุออกจากค่าพิกัด X และ Y ของอ็อบเจ็กต์ [Point](../) ที่ระบุโดยตรง

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| point | const [Point](../)\& | จุดที่จะทำการแปล |
| size | const [Size](../../size/)\& | อ็อบเจ็กต์ [Size](../../size/) ที่ระบุค่าที่จะลบออกจากค่าพิกัดของ **point** |

### ค่าที่คืน

อ็อบเจ็กต์ [Point](../) ใหม่ที่ค่าพิกัด X มีค่าเท่ากับผลลัพธ์ของการลบค่าความกว้างของ **size** จากค่าพิกัด X ของ **point** และค่าพิกัด Y มีค่าเท่ากับผลลัพธ์ของการลบค่าความสูงของ **size** จากค่าพิกัด Y ของ **point**

## ดูเพิ่มเติม

* คลาส [Point](../)
* คลาส [Size](../../size/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)