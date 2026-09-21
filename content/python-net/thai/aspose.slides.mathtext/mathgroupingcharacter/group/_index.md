---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathgroupingcharacter/group/
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
วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระกลุ่มเช่นวงเล็บปีกกาล่างหรืออักขระอื่น

### คืนค่า

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| character | **char** | อักขระกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่นๆ |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวในแนวตั้งของอักขระกลุ่ม.<br/><br/>            ระบุตำแหน่งการจัดแนวของวัตถีเทียบกับเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถี, <br/><br/>            VerticalJustification ของ Top หมายความว่าบนของวัตถีอยู่บนเส้นฐาน;<br/><br/>            เมื่อ VerticalJustification ตั้งเป็น Bottom, ส่วนล่างของวัตถีอยู่บนเส้นฐาน |



### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)