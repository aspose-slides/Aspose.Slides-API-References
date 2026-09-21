---
title: init_font_scheme_from method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.theme/overridetheme/init_font_scheme_from/
weight: 70
---
## init_font_scheme_from(self, font_scheme) {#ifontscheme}
เริ่มต้น FontScheme ด้วยอ็อบเจกต์ใหม่เพื่อแทนที่ FontScheme ของ InheritedTheme.

```python
def init_font_scheme_from(self, font_scheme):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| font_scheme | [`IFontScheme`](/slides/python-net/th/aspose.slides.theme/ifontscheme) | ข้อมูลสำหรับการเริ่มต้นจาก. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | จะถูกโยนถ้า FontScheme ถูกเริ่มต้นแล้ว (ไม่เป็น None). |
| **RuntimeError(Proxy error(ArgumentNullException))** | จะถูกโยนถ้าพารามิเตอร์ fontScheme เป็น None. |

### ดูเพิ่มเติม
* คลาส [`IFontScheme`](/slides/python-net/th/aspose.slides.theme/ifontscheme)
* คลาส [`OverrideTheme`](/slides/python-net/th/aspose.slides.theme/overridetheme)
* โมดูล [`aspose.slides.theme`](/slides/python-net/th/aspose.slides.theme)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)