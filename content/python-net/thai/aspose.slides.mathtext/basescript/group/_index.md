---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/basescript/group/
weight: 70
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาแบบล่าง

### คืนค่า

New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่มเช่นวงเล็บปีกกาแบบล่างหรืออักขระอื่น

### คืนค่า

New instance of type [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | ตัวอักษรการจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออักขระอื่นๆ |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของตัวอักษรการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดตำแหน่งแนวตั้งของตัวอักษรกลุ่ม.<br/><br/>            ระบุการจัดแนวของวัตถิตามเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่อตัวอักษรกลุ่มอยู่เหนือวัตถุ, <br/><br/>            VerticalJustification ของ Top หมายถึงส่วนบนของวัตถุตั้งอยู่บนเส้นฐาน;<br/><br/>            เมื่อตั้งค่า VerticalJustification เป็น Bottom ส่วนล่างของวัตถุอยู่บนเส้นฐาน |



### ดูเพิ่มเติม
* คลาส [`BaseScript`](/slides/python-net/th/aspose.slides.mathtext/basescript)
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)