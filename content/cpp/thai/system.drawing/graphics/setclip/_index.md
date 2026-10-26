---
title: SetClip()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดช่วงการคลิปของพื้นผิวการวาดที่แสดงโดยวัตถุ Graphics ปัจจุบันให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งผสานช่วงการคลิปปัจจุบันและช่วงที่ระบุ
type: docs
weight: 690
url: /th/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) เมธอด

กำหนดช่วงการคลิปรายการวาดที่แสดงโดยวัตถุปัจจุบัน [Graphics](../) ให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมช่วงการคลิปปัจจุบันและช่วงที่ระบุ

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | ระบุช่วงที่จะทำการผสาน |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | ระบุการดำเนินการผสาน |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) เมธอด

กำหนดช่วงการคลิปรายการวาดที่แสดงโดยวัตถุปัจจุบัน [Graphics](../) ให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมช่วงการคลิปปัจจุบันและช่วงที่ระบุ

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | ระบุช่วงที่จะทำการผสาน |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | ระบุการดำเนินการผสาน |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) เมธอด

กำหนดช่วงการคลิปรายการวาดที่แสดงโดยวัตถุปัจจุบัน [Graphics](../) ให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมช่วงการคลิปปัจจุบันและช่วงที่ระบุ

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | ระบุช่วงที่จะทำการผสาน |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | ระบุการดำเนินการผสาน |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) เมธอด

ยังไม่ได้ดำเนินการ

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) เมธอด

กำหนดช่วงการคลิปรายการวาดที่แสดงโดยวัตถุปัจจุบัน [Graphics](../) ให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมช่วงการคลิปปัจจุบันและช่วงที่ระบุโดยกราฟิกส์พาธ

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | ระบุช่วงที่จะทำการผสาน |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | ระบุการดำเนินการผสาน |

## ดูเพิ่มเติม

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)