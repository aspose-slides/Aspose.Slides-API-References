---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathsubscriptelement/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ bottom curly bracket

### ผลลัพธ์

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น bottom curly bracket หรืออักขระอื่น

### ผลลัพธ์

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| character | **char** | อักขระการจัดกลุ่ม เช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่น ๆ |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของอักขระกลุ่ม.<br/><br/>กำหนดการจัดตำแหน่งของวัตถุตามเส้นฐาน.<br/><br/>ตัวอย่างเช่นเมื่ออักขระกลุ่มอยู่เหนือวัตถุ,<br/><br/>VerticalJustification ของ Top หมายถึงส่วนบนของวัตถุอยู่บนเส้นฐาน;<br/><br/>เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom ส่วนล่างของวัตถุจะอยู่บนเส้นฐาน |



### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathSubscriptElement`](/slides/python-net/th/aspose.slides.mathtext/mathsubscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)