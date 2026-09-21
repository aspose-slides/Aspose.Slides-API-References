---
title: OverrideTheme class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.theme/overridetheme/
---
## OverrideTheme คลาส

แสดงธีมที่กำลังแทนที่

**การสืบทอด:**[`OverrideTheme`](/slides/python-net/th/aspose.slides.theme/overridetheme) → [`Theme`](/slides/python-net/th/aspose.slides.theme/theme)

The OverrideTheme type exposes the following members:

## Properties

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`color_scheme`](/slides/python-net/th/aspose.slides.theme/overridetheme/color_scheme/) | คืนค่าโครงร่างสี.<br/>            อ่านอย่างเดียว [`IColorScheme`](/slides/python-net/th/aspose.slides.theme/icolorscheme). |
| [`font_scheme`](/slides/python-net/th/aspose.slides.theme/overridetheme/font_scheme/) | คืนค่าโครงร่างแบบอักษร.<br/>            อ่านอย่างเดียว [`IFontScheme`](/slides/python-net/th/aspose.slides.theme/ifontscheme). |
| [`format_scheme`](/slides/python-net/th/aspose.slides.theme/overridetheme/format_scheme/) | คืนค่าโครงร่างรูปแบบรูปร่าง.<br/>            อ่านอย่างเดียว [`IFormatScheme`](/slides/python-net/th/aspose.slides.theme/iformatscheme). |
| [`presentation`](/slides/python-net/th/aspose.slides.theme/overridetheme/presentation/) | คืนค่าการนำเสนอแม่แบบ.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`is_empty`](/slides/python-net/th/aspose.slides.theme/overridetheme/is_empty/) | ค่าจริงหมายความว่า ColorScheme, FontScheme, FormatScheme เป็น None และการแทนที่ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้ถูกปิดใช้งาน.<br/>            อ่านอย่างเดียว **bool**. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/get_effective/#) | รับข้อมูลธีมที่มีผลโดยใช้การสืบทอดที่ถูกนำมาใช้. |
| [`init_color_scheme(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_color_scheme/#) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ ColorScheme ของ InheritedTheme. |
| [`init_color_scheme_from(self, color_scheme)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_color_scheme_from/#icolorscheme) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ ColorScheme ของ InheritedTheme. |
| [`init_color_scheme_from_inherited(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_color_scheme_from_inherited/#) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ ColorScheme ของ InheritedTheme. และกำหนดค่าข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ ColorScheme ของ InheritedTheme. |
| [`init_font_scheme(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_font_scheme/#) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ FontScheme ของ InheritedTheme. |
| [`init_font_scheme_from(self, font_scheme)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_font_scheme_from/#ifontscheme) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ FontScheme ของ InheritedTheme. |
| [`init_font_scheme_from_inherited(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_font_scheme_from_inherited/#) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ FontScheme ของ InheritedTheme. และกำหนดค่าข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ FontScheme ของ InheritedTheme. |
| [`init_format_scheme(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_format_scheme/#) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ FormatScheme ของ InheritedTheme. |
| [`init_format_scheme_from(self, format_scheme)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_format_scheme_from/#iformatscheme) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ FormatScheme ของ InheritedTheme. |
| [`init_format_scheme_from_inherited(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/init_format_scheme_from_inherited/#) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่เพื่อแทนที่ FormatScheme ของ InheritedTheme. และกำหนดค่าข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ FormatScheme ของ InheritedTheme. |
| [`clear(self)`](/slides/python-net/th/aspose.slides.theme/overridetheme/clear/#) | ตั้งค่า ColorScheme, FontScheme, FormatScheme เป็น None เพื่อปิดการแทนที่ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้. |

### ดูเพิ่มเติม
* คลาส [`OverrideTheme`](/slides/python-net/th/aspose.slides.theme/overridetheme)
* คลาส [`Theme`](/slides/python-net/th/aspose.slides.theme/theme)
* โมดูล [`aspose.slides.theme`](/slides/python-net/th/aspose.slides.theme)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)