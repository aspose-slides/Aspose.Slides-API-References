---
title: Complement()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แทนที่ region ที่เป็นตัวแทนของวัตถุปัจจุบันด้วยส่วนของ region ที่กำหนดโดย recangle ที่ระบุซึ่งไม่ตัดกันกับ region นี้.
type: docs
weight: 131
url: /th/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) เมธอด


แทนที่ region ที่เป็นตัวแทนของวัตถุปัจจุบันด้วยส่วนของ region ที่กำหนดโดย recangle ที่ระบุซึ่งไม่ตัดกันกับ region นี้

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | recangle ที่กำหนด region เพื่อทำการ complement |

## Region::Complement(const Rectangle\&) เมธอด


แทนที่ region ที่เป็นตัวแทนของวัตถุปัจจุบันด้วยส่วนของ region ที่กำหนดโดย recangle ที่ระบุซึ่งไม่ตัดกันกับ region นี้

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | recangle ที่กำหนด region เพื่อทำการ complement |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) เมธอด


แทนที่ region ที่เป็นตัวแทนของวัตถุปัจจุบันด้วยส่วนของ region ที่กำหนดโดย path ที่ระบุซึ่งไม่ตัดกันกับ region นี้

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | path ที่กำหนด region เพื่อทำการ complement |

## Region::Complement(const SharedPtr\<Region\>\&) เมธอด


แทนที่ region ที่เป็นตัวแทนของวัตถุปัจจุบันด้วยส่วนของ region ที่ระบุซึ่งไม่ตัดกันกับ region นี้

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | region ที่จะทำการ complement |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)