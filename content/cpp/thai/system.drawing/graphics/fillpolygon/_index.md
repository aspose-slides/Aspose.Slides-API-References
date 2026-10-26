---
title: FillPolygon()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เติมส่วนภายในของรูปหลายเหลี่ยมที่ระบุโดยใช้แปรงที่ระบุ
type: docs
weight: 417
url: /th/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) เมธอด

เติมส่วนภายในของรูปหลายเหลี่ยมที่ระบุโดยใช้แปรงที่ระบุ

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | วัตถุ [Brush](../../brush/) ที่ระบุพารามิเตอร์ของการเติม |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | อาเรย์ที่ประกอบด้วยจุดที่กำหนดรูปหลายเหลี่ยม |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | โหมดการเติม |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) เมธอด

เติมส่วนภายในของรูปหลายเหลี่ยมที่ระบุโดยใช้แปรงที่ระบุ

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | วัตถุ [Brush](../../brush/) ที่ระบุพารามิเตอร์ของการเติม |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | อาเรย์ที่ประกอบด้วยจุดที่กำหนดรูปหลายเหลี่ยม |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | โหมดการเติม |

## ดูเพิ่มเติม

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Brush](../../brush/)
* คลาส [Point](../../point/)
* คลาส [Graphics](../)
* คลาส [PointF](../../pointf/)
* เนมสเปซ [System::Drawing](../../)
* Library [Aspose.Slides](../../../)