---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง

### คืนค่า

New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรกลุ่ม เช่น วงเล็บปีกกาล่างหรืออักขระอื่น

### คืนค่า

New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| character | **char** | ตัวอักษรที่ใช้กลุ่ม เช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่น ๆ |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของตัวอักษรที่ใช้กลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดตำแหน่งแนวตั้งของตัวอักษรกลุ่ม.<br/><br/>            ระบุการจัดแนวของวัตถุตาม baseline.<br/><br/>            ตัวอย่าง เช่น เมื่ออักษรกลุ่มอยู่เหนือวัตถุ, <br/><br/>            VerticalJustification ของ Top หมายถึงด้านบนของวัตถุอยู่บน baseline;<br/><br/>            เมื่อตั้งค่า VerticalJustification เป็น Bottom, ส่วนล่างของวัตถุจะอยู่บน baseline |



### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathSuperscriptElement`](/slides/python-net/th/aspose.slides.mathtext/mathsuperscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)