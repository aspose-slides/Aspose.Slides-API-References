---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathradical/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง

### คืนค่า

New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรจัดกลุ่ม เช่น วงเล็บโค้งล่าง หรืออักษรอื่น

### คืนค่า

New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | อักขระจัดกลุ่ม เช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่นใด |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของตัวอักษรกลุ่ม.<br/><br/>            ระบุตำแหน่งการจัดแนวของวัตถุเมื่อเทียบกับเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่อตัวอักษรกลุ่มอยู่เหนือวัตถุ, <br/><br/>            VerticalJustification of Top หมายถึงด้านบนของวัตถุอยู่บนเส้นฐาน;<br/><br/>            เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom, ด้านล่างของวัตถุอยู่บนเส้นฐาน |



### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathRadical`](/slides/python-net/th/aspose.slides.mathtext/mathradical)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)