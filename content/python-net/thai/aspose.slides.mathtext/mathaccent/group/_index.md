---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
Places this element in a group using a bottom curly bracket

### Returns
New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Places this element in a group using a grouping character such as bottom curly bracket or another

### Returns
New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| character | **char** | ตัวอักษรจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่น ๆ |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของตัวอักษรจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของตัวอักษรกลุ่ม.<br/><br/>            ระบุการจัดตำแหน่งของวัตถุสัมพันธ์กับเส้นฐาน.<br/><br/>            ตัวอย่างเช่นเมื่อตัวอักษรกลุ่มอยู่เหนือวัตถุ, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathAccent`](/slides/python-net/th/aspose.slides.mathtext/mathaccent)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)