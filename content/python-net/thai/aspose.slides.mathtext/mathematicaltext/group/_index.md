---
title: group method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathematicaltext/group/
weight: 80
---
## group(self) {#}
วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง

### คืนค่า

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออื่น ๆ

### คืนค่า

อินสแตนซ์ใหม่ของประเภท [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| character | **char** | อักขระการจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่น ๆ |
| position | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | ตำแหน่งของอักขระการจัดกลุ่ม |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions) | การจัดแนวแนวตั้งของอักขระกลุ่ม.<br/><br/>            ระบุตำแหน่งการจัดแนวของอ็อบเจกต์สัมพันธ์กับเส้นฐาน.<br/><br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจกต์, <br/><br/>            VerticalJustification ของ Top หมายถึงส่วนบนของอ็อบเจกต์อยู่บนเส้นฐาน;<br/><br/>            เมื่อ VerticalJustification ถูกตั้งเป็น Bottom ส่วนล่างของอ็อบเจกต์จะอยู่บนเส้นฐาน |



### ดูเพิ่มเติม
* คลาส [`IMathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/imathgroupingcharacter)
* คลาส [`MathematicalText`](/slides/python-net/th/aspose.slides.mathtext/mathematicaltext)
* enumeration [`MathTopBotPositions`](/slides/python-net/th/aspose.slides.mathtext/mathtopbotpositions)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)