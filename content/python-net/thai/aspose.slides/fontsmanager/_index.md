---
title: FontsManager class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/fontsmanager/
---
## FontsManager คลาส

จัดการแบบอักษรทั่วทั้งงานนำเสนอ。

ประเภท FontsManager เปิดเผยสมาชิกต่อไปนี้：

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/th/aspose.slides/fontsmanager/font_subst_rule_list/) | การแทนที่แบบอักษรที่ใช้เมื่อตีพิมพ์.<br/>            อ่าน/เขียน [`IFontSubstRuleCollection`](/slides/python-net/th/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/th/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | แสดงคอลเลกชันของกฎ FontFallBack ของผู้ใช้สำหรับจัดการคอลเลกชันของแบบอักษรเพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback<br/>            อ่าน/เขียน [`IFontFallBackRulesCollection`](/slides/python-net/th/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/th/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | ระบุว่าจะให้แบบอักษรที่ลงทะเบียนถูกใช้เป็นค่าเริ่มต้นเหนือแบบอักษรที่ฝังไว้ที่มีชื่อและสไตล์เดียวกันหรือไม่.<br/>            เมื่อเปิดใช้งาน แบบอักษรที่ฝังที่ตรงกันจะถูกแทนที่ด้วยแบบอักษรที่ลงทะเบียนที่สอดคล้องกันอย่างชั่วคราวระหว่างการส่งออก. |

## วิธีการ

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/th/aspose.slides/fontsmanager/get_substitutions/#) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ในการตีพิมพ์ของงานนำเสนอ. |
| [`get_substitutions(self, slides)`](/slides/python-net/th/aspose.slides/fontsmanager/get_substitutions/#listint) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ระหว่างการตีพิมพ์ของสไลด์ที่ระบุ. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>            โปรดจำไว้เมื่อคัดลอกแบบอักษรใด ๆ เนื่องจากส่วนมากมีลิขสิทธิ์. ก่อนหน้าให้ค้นหาใบอนุญาตของ <br/>            แบบอักษรและตรวจสอบว่ามันสามารถถูกโอนย้ายไปยังเครื่องอื่นได้โดยเสรี. ข้อยกเว้น ArgumentException อาจถูกโยนขึ้นหากข้อมูลแบบอักษรว่างหรือแบบอักษรนี้ได้ถูกฝังไว้แล้ว |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>            โปรดจำไว้เมื่อคัดลอกแบบอักษรใด ๆ เนื่องจากส่วนมากมีลิขสิทธิ์. ก่อนหน้าให้ค้นหาใบอนุญาตของ <br/>            แบบอักษรและตรวจสอบว่ามันสามารถถูกโอนย้ายไปยังเครื่องอื่นได้โดยเสรี. ข้อยกเว้น ArgumentException อาจถูกโยนขึ้นหากข้อมูลแบบอักษรว่างหรือแบบอักษรนี้ได้ถูกฝังไว้แล้ว |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/th/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | แทนที่แบบอักษรในงานนำเสนอ |
| [`replace_font(self, subst_rule)`](/slides/python-net/th/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ใน [`FontSubstRule`](/slides/python-net/th/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/th/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ในคอลเลกชันของ [`FontSubstRule`](/slides/python-net/th/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/th/aspose.slides/fontsmanager/get_fonts/#) | คืนค่าแบบอักษรที่ใช้ในงานนำเสนอ |
| [`get_embedded_fonts(self)`](/slides/python-net/th/aspose.slides/fontsmanager/get_embedded_fonts/#) | คืนค่าแบบอักษรที่ฝังอยู่ในงานนำเสนอ |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/th/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | ลบแบบอักษรที่ฝังไว้ |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/th/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | เรียกคืนอาร์เรย์ไบต์ที่แสดงข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่ระบุ. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/th/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | กำหนดระดับการฝังของแบบอักษรจากอาร์เรย์ไบต์และชื่อแบบอักษรที่ให้. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)