---
title: IPortionFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iportionformat/
---
## IPortionFormat คลาส

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. แตกต่างจาก [`IPortionFormatEffectiveData`](/slides/python-net/th/aspose.slides/iportionformateffectivedata), คุณสมบัติต่าง ๆ ของคลาสนี้สามารถเขียนได้.

ประเภท IPortionFormat เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`bookmark_id`](/slides/python-net/th/aspose.slides/iportionformat/bookmark_id/) | คืนค่าหรือกำหนดตัวระบุ bookmark.<br/>            อ่าน/เขียน **str**. |
| [`smart_tag_clean`](/slides/python-net/th/aspose.slides/iportionformat/smart_tag_clean/) | กำหนดว่าควรทำความสะอาด smart tag หรือไม่. ไม่มีการสืบทอดที่ใช้.<br/>            อ่าน/เขียน **bool**. |
| [`line_format`](/slides/python-net/th/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/th/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/th/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/th/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/th/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/th/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/th/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/th/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/th/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/th/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/th/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/th/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/th/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/th/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/th/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/th/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/th/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/th/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/th/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/th/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/th/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/th/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/th/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/th/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/th/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/th/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/th/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/iportionformat/hyperlink_manager/) |  |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides/iportionformat/get_effective/#) | รับข้อมูลการจัดรูปแบบส่วนที่มีผลโดยมีการสืบทอดที่ใช้. |


### หมายเหตุ

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนเฉพาะ. ซึ่งหมายความว่า
            ไม่มีการสืบทอดที่ใช้เมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอดคุณต้องใช้เมธอด [`IPortionFormat.get_effective`](/slides/python-net/th/aspose.slides/iportionformat/get_effective) 
            ซึ่งจะคืนค่าอินสแตนซ์ [`IPortionFormatEffectiveData`](/slides/python-net/th/aspose.slides/iportionformateffectivedata).

### ดูเพิ่มเติม
* คลาส [`IPortionFormatEffectiveData`](/slides/python-net/th/aspose.slides/iportionformateffectivedata)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)