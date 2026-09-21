---
title: init_color_scheme_from method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.theme/overridetheme/init_color_scheme_from/
weight: 40
---
## init_color_scheme_from(self, color_scheme) {#icolorscheme}
เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ ColorScheme ของ InheritedTheme.

```python
def init_color_scheme_from(self, color_scheme):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| color_scheme | [`IColorScheme`](/slides/python-net/th/aspose.slides.theme/icolorscheme) | ข้อมูลสำหรับการเริ่มต้นจาก |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | จะถูกขว้างถ้า ColorScheme ได้รับการเริ่มต้นแล้ว (ไม่เป็น None). |
| **RuntimeError(Proxy error(ArgumentNullException))** | จะถูกขว้างถ้า parameter colorScheme เป็น None. |

### ดูเพิ่มเติม
* คลาส [`IColorScheme`](/slides/python-net/th/aspose.slides.theme/icolorscheme)
* คลาส [`OverrideTheme`](/slides/python-net/th/aspose.slides.theme/overridetheme)
* โมดูล [`aspose.slides.theme`](/slides/python-net/th/aspose.slides.theme)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)