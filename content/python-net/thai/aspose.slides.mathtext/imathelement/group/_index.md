---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/imathelement/group/
weight: 70
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงโค้งล่าง

### คืนค่า

อินสแตนซ์ใหม่ของชนิด [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรกำหนดกลุ่ม เช่น วงโค้งล่าง หรืออื่น ๆ

### คืนค่า

อินสแตนซ์ใหม่ของชนิด [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | อักขระกำหนดกลุ่ม เช่น BOTTOM CURLY BRACKET (U+23DF) หรืออักขระอื่นใด |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระกำหนดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของอักขระกลุ่ม<br/><br/>            ระบุการจัดตำแหน่งของวัตถุสัมพันธ์กับ baseline<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ, <br/><br/>            VerticalJustification ของ Top หมายถึงว่าบนของวัตถุตั้งอยู่บน baseline;<br/><br/>            เมื่อ VerticalJustification ตั้งเป็น Bottom, ส่วนล่างของวัตถุตั้งอยู่บน baseline |

### ดูเพิ่มเติม
* คลาส [`IMathElement`](/slides/python-net/th/aspose.slides.mathtext/imathelement)
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)