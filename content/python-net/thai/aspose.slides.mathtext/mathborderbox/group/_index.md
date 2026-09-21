---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathborderbox/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง

### คืนค่า
อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออื่น ๆ

### คืนค่า
อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| character | **char** | อักขระการจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่นใด |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวตั้งของอักขระกลุ่ม.<br/><br/>            ระบุการจัดแนวของอ็อบเจ็กต์สัมพันธ์กับ baseline.<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์, <br/><br/>            VerticalJustification ของ Top หมายความว่าด้านบนของอ็อบเจ็กต์อยู่บน baseline;<br/><br/>            เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom ด้านล่างของอ็อบเจ็กต์อยู่บน baseline |

### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathBorderBox`](/slides/python-net/th/aspose.slides.mathtext/mathborderbox)
* enum [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)