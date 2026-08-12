---
title: Add()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เพิ่มค่าความกว้างและความสูงของวัตถุ Size ที่ระบุเข้าไปในค่าพิกัด X และ Y ของวัตถุ Point ที่ระบุอย่างสอดคล้องกัน
type: docs
weight: 183
url: /th/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) เมธอด

เพิ่มค่าความกว้างและความสูงของวัตถุ [Size](../../size/) ที่ระบุเข้าไปในค่าพิกัด X และ Y ของวัตถุ [Point](../) ที่ระบุอย่างสอดคล้องกัน

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | จุดที่ต้องการแปลงตำแหน่ง |
| size | const [Size](../../size/)\& | วัตถุ [Size](../../size/) ที่ระบุค่าที่จะเพิ่มเข้าไปในค่าพิกัดของ **point** |

### ค่าที่คืน

วัตถุ [Point](../) ใหม่ที่ค่าพิกัด X มีค่าเท่ากับผลรวมของค่าพิกัด X ของ **point** และค่าความกว้างของ **size** และค่าพิกัด Y มีค่าเท่ากับผลรวมของค่าพิกัด Y ของ **point** และค่าความสูงของ **size**

## ดูเพิ่มเติม

* คลาส [Point](../)
* คลาส [Size](../../size/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)