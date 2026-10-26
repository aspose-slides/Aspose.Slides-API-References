---
title: Rectangle()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: สร้างอินสแตนซ์ใหม่ของวัตถุ Rectangle ที่แสดงสี่เหลี่ยมโดยมีพิกัด X และ Y และค่าความกว้างและความสูงตั้งเป็น 0.
type: docs
weight: 1
url: /th/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของวัตถุ [Rectangle](../) ที่แสดงสี่เหลี่ยมที่มีค่าพิกัด X และ Y และค่าความกว้างและความสูงตั้งเป็น 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของวัตถุ [Rectangle](../) ที่แสดงสี่เหลี่ยมโดยมีพิกัดของมุมซ้ายบนที่ระบุและความกว้างและความสูง

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | int | ค่าของพิกัด X ของมุมซ้ายบนของสี่เหลี่ยม |
| y | int | ค่าของพิกัด Y ของมุมซ้ายบนของสี่เหลี่ยม |
| width | int | ความกว้างของสี่เหลี่ยม |
| height | int | ความสูงของสี่เหลี่ยม |

## Rectangle::Rectangle(const Point\&, const Size\&) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของวัตถุ [Rectangle](../) ที่แสดงสี่เหลี่ยมโดยมีพิกัดของมุมซ้ายบนระบุเป็นอินสแตนซ์ของคลาส [Point](../../point/) และความกว้างและความสูงเป็นอินสแตนซ์ของคลาส [Size](../../size/)

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### อาร์กิวเม้นต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| location | const [Point](../../point/)\& | ระบุตำแหน่งของมุมซ้ายบนของสี่เหลี่ยม |
| size | const [Size](../../size/)\& | ระบุความกว้างและความสูงของสี่เหลี่ยม |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของวัตถุ [Rectangle](../) ที่แสดงสี่เหลี่ยมที่เทียบเท่ากับสี่เหลี่ยมที่ระบุ

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | อินสแตนซ์ของคลาส **System::Windows::Forms::Screen::Rectangle_** ที่ระบุตำแหน่งและขนาดของสี่เหลี่ยมที่วัตถุที่กำลังก่อสร้างจะแสดง |

## ดูเพิ่มเติม

* คลาส [Rectangle](../)
* คลาส [Point](../../point/)
* คลาส [Size](../../size/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)