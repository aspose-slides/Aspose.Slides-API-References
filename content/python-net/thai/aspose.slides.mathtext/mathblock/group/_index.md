---
title: group method
second_title: อ้างอิง API ของ Aspose.Slides for Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.mathtext/mathblock/group/
weight: 130
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
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออื่น ๆ

### คืนค่า

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| character | **char** | ตัวอักษรจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่น ๆ |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของตัวอักษรจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของตัวอักษรกลุ่ม.<br/><br/>            ระบุตำแหน่งการจัดวางของอ็อบเจ็กต์สัมพันธ์กับเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์, <br/><br/>            VerticalJustification ของ Top หมายความว่าบนของอ็อบเจ็กต์อยู่บนเส้นฐาน;<br/><br/>            เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom, ด้านล่างของอ็อบเจ็กต์อยู่บนเส้นฐาน |

### ดูเพิ่มเติม
* class [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathBlock`](/slides/python-net/th/aspose.slides.mathtext/mathblock)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)