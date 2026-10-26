---
title: FillClosedCurve()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: วาดเส้นโค้งปิดโดยใช้แปรงที่ระบุ.
type: docs
weight: 807
url: /th/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) เมธอด

วาดเส้นโค้งปิดโดยใช้แปรงที่ระบุ.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | แปรงที่จะใช้เมื่อวาดเส้นโค้ง |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนดเส้นโค้ง |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ละเลย |
| tension | **float** | ค่าที่ระบุความตึงของเส้นโค้ง |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) เมธอด

วาดเส้นโค้งปิดโดยใช้แปรงที่ระบุ.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | แปรงที่จะใช้เมื่อวาดเส้นโค้ง |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนดเส้นโค้ง |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ละเลย |
| tension | **float** | ค่าที่ระบุความตึงของเส้นโค้ง |

## ดูเพิ่มเติม

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [Graphics](../)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)