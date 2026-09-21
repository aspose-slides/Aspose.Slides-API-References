---
title: MathDelimiter constructor
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
เริ่มต้น MathDelimiter ด้วย element ที่ระบุเป็นอากิวเมนต์ฐานเดียว


```python
def __init__(self, element):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/th/aspose.slides.mathtext/imathelement) | อิลิเมนต์ฐานที่ delimiter ถูกนำไปใช้ สามารถเป็น None ได้ |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดข้อผิดพลาดเมื่อ `element` เป็นคอนเทนเนอร์ของอิลิเมนต์อื่น ๆ เช่น MathBlock ในกรณีนี้คุณต้องเรียกคอนสตรักเตอร์ที่แตกต่างด้วยอากิวเมนต์ประเภท IEnumerable |

### See Also
* คลาส [`IMathElement`](/slides/python-net/th/aspose.slides.mathtext/imathelement)
* คลาส [`MathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)