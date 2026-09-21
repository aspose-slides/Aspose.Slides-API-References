---
title: enclose method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
ใส่อิลิเมนต์คณิตศาสตร์ในวงเล็บ

### คืนค่า

อิลิเมนต์คณิตศาสตร์ประเภท [`IMathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter) ที่รวมวงเล็บไว้



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
ใส่อิลิเมนต์คณิตศาสตร์ในอักขระที่กำหนด เช่น วงเล็บหรืออักขระอื่น ๆ เป็นกรอบ

### คืนค่า

หาก `beginning_character` และ `ending_character` เป็น `None`,
            จะกำหนดค่าให้กับคุณสมบัติเพียงอย่างเดียวและไม่สร้างอ็อบเจกต์ใหม่ (คืนค่าตัวอินสแตนซ์นี้)
            มิฉะนั้น จะคืนค่าอิลิเมนต์คณิตศาสตร์ใหม่ประเภท Delimiter ที่รวมอักขระที่ระบุเป็นกรอบ
            และอินสแตนซ์ของ [`MathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter) ที่อยู่ภายในกรอบ



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| พารามิเตอร์ | ชนิด | รายละเอียด |
| :- | :- | :- |
| beginning_character | **char** | อักษรเริ่มต้น (โดยทั่วไปคือวงเล็บเปิด) |
| ending_character | **char** | อักษรสิ้นสุด (โดยทั่วไปคือวงเล็บปิด) |



### ดูเพิ่มเติม
* class [`IMathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter)
* class [`MathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter)
* module [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)