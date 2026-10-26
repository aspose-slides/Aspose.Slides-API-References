---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathleftsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาตรงด้านล่าง

### Returns
อินสแตนซ์ใหม่ของชนิด [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บปีกกาตรงด้านล่างหรืออักขระอื่น

### Returns
อินสแตนซ์ใหม่ของชนิด [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | อักขระการจัดกลุ่ม เช่น BOTTOM CURLY BRACKET (U+23DF) หรืออักขระอื่น |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดชิดแนวตั้งของอักขระกลุ่ม.<br/><br/>            ระบุการจัดตำแหน่งของวัตถุตามเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ, <br/><br/>            VerticalJustification ของ Top หมายถึงด้านบนของวัตถุอยู่บนเส้นฐาน;<br/><br/>            เมื่อ VerticalJustification ตั้งค่าเป็น Bottom ด้านล่างของวัตถุอยู่บนเส้นฐาน |

### See Also
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathLeftSubSuperscriptElement`](/slides/python-net/th/aspose.slides.mathtext/mathleftsubsuperscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* ม็อดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)