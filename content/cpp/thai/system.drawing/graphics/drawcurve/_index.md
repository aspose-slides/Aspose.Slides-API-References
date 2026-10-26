---
title: DrawCurve()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: วาดสพลายน์โดยใช้ปากกาที่ระบุ
type: docs
weight: 794
url: /th/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) เมธอด

วาดสพลายน์โดยใช้ปากกาที่ระบุ

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้เมื่อวาดสพลายน์ |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนดสพลายน์ |
| tension | **float** | ค่าที่ระบุความตึงของสพลายน์ |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) เมธอด

วาดสพลายน์โดยใช้ปากกาที่ระบุ

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้เมื่อวาดสพลายน์ |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนดสพลายน์ |
| tension | **float** | ค่าที่ระบุความตึงของสพลายน์ |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) เมธอด

วาดสพลายน์โดยใช้ปากกาที่ระบุ

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้เมื่อวาดสพลายน์ |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนดสพลายน์ |
| offset | **int32_t** | การออฟเซ็ตจากองค์ประกอบแรกในอาร์เรย์ **points** |
| numberOfSegments | **int32_t** | จำนวนส่วนที่รวมไว้ในเส้นโค้ง |
| tension | **float** | ค่าที่ระบุความตึงของสพลายน์ |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) เมธอด

วาดสพลายน์โดยใช้ปากกาที่ระบุ

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | ปากกาที่ใช้เมื่อวาดสพลายน์ |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) ของจุดที่กำหนดสพลายน์ |
| offset | **int32_t** | การออฟเซ็ตจากองค์ประกอบแรกในอาร์เรย์ **points** |
| numberOfSegments | **int32_t** | จำนวนส่วนที่รวมไว้ในเส้นโค้ง |
| tension | **float** | ค่าที่ระบุความตึงของสพลายน์ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)