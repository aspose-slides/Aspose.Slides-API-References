---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บก้นโค้งด้านล่าง

### Returns

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักขระสำหรับจัดกลุ่ม เช่น วงเล็บก้นโค้งด้านล่างหรืออักขระอื่นๆ

### Returns

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | ตัวอักษรสำหรับจัดกลุ่ม เช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่นใด |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของอักขระกลุ่ม.<br/><br/>            กำหนดการจัดตำแหน่งของวัตถุสัมพันธ์กับเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ <br/><br/>            การจัดแนวแนวตั้งของ Top หมายถึงส่วนบนของวัตถุตกบนเส้นฐาน;<br/><br/>            เมื่อการจัดแนวแนวตั้งตั้งเป็น Bottom ส่วนล่างของวัตถุจะอยู่บนเส้นฐาน |



### See Also
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathPhantom`](/slides/python-net/th/aspose.slides.mathtext/mathphantom)
* การนับจำนวน [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)