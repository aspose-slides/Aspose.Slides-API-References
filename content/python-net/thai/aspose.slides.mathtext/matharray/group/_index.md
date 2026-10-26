---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/matharray/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้เข้าในกลุ่มโดยใช้วงเล็บปีกกาตรงด้านล่าง

### คืนค่า
New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้เข้าในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่ม เช่น วงเล็บปีกกาตรงด้านล่างหรืออื่น ๆ

### คืนค่า
New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| character | **char** | อักขระการจัดกลุ่ม เช่น วงเล็บปีกกาตรงด้านล่าง (U+23DF) หรืออื่นใด |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของอักขระกลุ่ม.<br/><br/>            ระบุตำแหน่งการจัดแนวของอ็อบเจ็กต์สัมพันธ์กับเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์, <br/><br/>            VerticalJustification ของ Top หมายถึงว่าด้านบนของอ็อบเจ็กต์อยู่บนเส้นฐาน;<br/><br/>            เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom, ด้านล่างของอ็อบเจ็กต์อยู่บนเส้นฐาน |

### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathArray`](/slides/python-net/th/aspose.slides.mathtext/matharray)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)