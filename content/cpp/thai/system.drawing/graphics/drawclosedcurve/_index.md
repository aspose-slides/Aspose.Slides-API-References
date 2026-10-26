---
title: DrawClosedCurve()
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: วาด spline ปิดโดยใช้ปากกาที่ระบุ
type: docs
weight: 781
url: /th/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) เมธอด


วาดเส้น spline ปิดโดยใช้ปากกา (pen) ที่ระบุ

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | pen ที่ใช้เมื่อวาด spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนด spline |
| tension | **float** | ค่าที่ระบุความตึงของ spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ละเว้น |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) เมธอด


วาดเส้น spline ปิดโดยใช้ปากกา (pen) ที่ระบุ

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | pen ที่ใช้เมื่อวาด spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนด spline |
| tension | **float** | ค่าที่ระบุความตึงของ spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ละเว้น |

## ดูเพิ่มเติม

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Pen](../../pen/)
* คลาส [Point](../../point/)
* คลาส [Graphics](../)
* คลาส [PointF](../../pointf/)
* เนมสเปซ [System::Drawing](../../)
* Library [Aspose.Slides](../../../)