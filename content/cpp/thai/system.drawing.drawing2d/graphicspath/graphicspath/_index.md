---
title: GraphicsPath()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของคลาส GraphicsPath ด้วยโหมดการเติมที่ระบุ
type: docs
weight: 1
url: /th/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) constructor


สร้างอินสแตนซ์ใหม่ของคลาส [GraphicsPath](../) ด้วยโหมดการเติมที่ระบุ

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | ระบุว่าภายในของเส้นทางที่ปิดซึ่งแสดงโดยอ็อบเจกต์ที่กำลังสร้างควรเติมอย่างไร |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [GraphicsPath](../) ที่แสดงเส้นทางที่ระบุ

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | อาเรย์ที่ประกอบด้วยจุดที่ระบุเส้นทางที่อ็อบเจกต์ที่กำลังสร้างจะเป็นตัวแทน |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ที่ประกอบด้วยค่าที่ระบุประเภทของจุดที่สอดคล้องกันในอาเรย์ **pts** |
| fillMode | [FillMode](../../fillmode/) | ระบุว่าภายในของเส้นทางที่ปิดซึ่งแสดงโดยอ็อบเจกต์ที่กำลังสร้างควรเติมอย่างไร |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


สร้างอินสแตนซ์ใหม่ของอ็อบเจกต์ [GraphicsPath](../) ที่แสดงเส้นทางที่ระบุ

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | อาเรย์ที่ประกอบด้วยจุดที่ระบุเส้นทางที่อ็อบเจกต์ที่กำลังสร้างจะเป็นตัวแทน |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ที่ประกอบด้วยค่าที่ระบุประเภทของจุดที่สอดคล้องกันในอาเรย์ **pts** |
| fillMode | [FillMode](../../fillmode/) | ระบุว่าภายในของเส้นทางที่ปิดซึ่งแสดงโดยอ็อบเจกต์ที่กำลังสร้างควรเติมอย่างไร |

## GraphicsPath::GraphicsPath(const SkPath\&) constructor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## See Also

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)