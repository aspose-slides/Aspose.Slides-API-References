---
title: FontsManager class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/fontsmanager/
---
## FontsManager คลาส

Manages fonts across the presentation.

The FontsManager type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/th/aspose.slides/fontsmanager/font_subst_rule_list/) | การแทนที่แบบอักษรที่จะใช้เมื่อทำการเรนเดอร์.<br/>            อ่าน/เขียน [`IFontSubstRuleCollection`](/slides/python-net/th/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/th/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | แสดงคอลเลกชันของกฎ FontFallBack ของผู้ใช้สำหรับจัดการคอลเลกชันของแบบอักษรเพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback<br/>            อ่าน/เขียน [`IFontFallBackRulesCollection`](/slides/python-net/th/aspose.slides/ifontfallbackrulescollection). |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/th/aspose.slides/fontsmanager/get_substitutions/#) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ในการเรนเดอร์ของงานนำเสนอ. |
| [`get_substitutions(self, slides)`](/slides/python-net/th/aspose.slides/fontsmanager/get_substitutions/#listint) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ระหว่างการเรนเดอร์ของสไลด์ที่ระบุ. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>            โปรดจำไว้เมื่อคัดลอกแบบอักษรใด ๆ ว่ามักจะมีลิขสิทธิ์. ก่อนอื่นให้ค้นหาใบอนุญาตของ <br/>            แบบอักษรก่อนและตรวจสอบว่ามันสามารถโอนย้ายไปยังเครื่องอื่นได้อย่างอิสระ. ArgumentException สามารถถูกขว้างออกได้หาก font data เป็น None หรือแบบอักษรนี้ได้ถูกฝังแล้ว |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>            โปรดจำไว้เมื่อคัดลอกแบบอักษรใด ๆ ว่ามักจะมีลิขสิทธิ์. ก่อนอื่นให้ค้นหาใบอนุญาตของ <br/>            แบบอักษรก่อนและตรวจสอบว่ามันสามารถโอนย้ายไปยังเครื่องอื่นได้อย่างอิสระ. ArgumentException สามารถถูกขว้างออกได้หาก font data เป็น None หรือแบบอักษรนี้ได้ถูกฝังแล้ว |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/th/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | แทนที่แบบอักษรในงานนำเสนอ |
| [`replace_font(self, subst_rule)`](/slides/python-net/th/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [`FontSubstRule`](/slides/python-net/th/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/th/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [`FontSubstRule`](/slides/python-net/th/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/th/aspose.slides/fontsmanager/get_fonts/#) | คืนค่าแบบอักษรที่ใช้ในงานนำเสนอ |
| [`get_embedded_fonts(self)`](/slides/python-net/th/aspose.slides/fontsmanager/get_embedded_fonts/#) | คืนค่าแบบอักษรที่ฝังอยู่ในงานนำเสนอ |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/th/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | ลบแบบอักษรที่ฝังไว้ |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/th/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | ดึงอาร์เรย์ของไบต์ที่แทนข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรที่ระบุและ font data. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/th/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | กำหนดระดับการฝังของแบบอักษรจากอาร์เรย์ของไบต์และชื่อแบบอักษรที่ให้มา. |


### ดูเพิ่มเติม
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)