---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathfraction/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง

### คืนค่า
อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักขระการจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออักขระอื่น

### คืนค่า
อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| character | **char** | อักขระการจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออักขระอื่น |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของอักขระกลุ่ม.<br/><br/>            กำหนดการจัดตำแหน่งของวัตถุตามเส้นฐาน.<br/><br/>            ตัวอย่างเช่นเมื่ออักขระกลุ่มอยู่เหนือวัตถุ, <br/><br/>            VerticalJustification ของ Top แสดงว่าบริเวณบนของวัตถุอยู่บนเส้นฐาน;<br/><br/>            เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom, ส่วนล่างของวัตถุอยู่บนเส้นฐาน |

### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathFraction`](/slides/python-net/th/aspose.slides.mathtext/mathfraction)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)