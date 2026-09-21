---
title: IFontsManager class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ifontsmanager/
---
## คลาส IFontsManager

จัดการแบบอักษรทั่วทั้งงานนำเสนอ

ประเภท IFontsManager เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/th/aspose.slides/ifontsmanager/font_subst_rule_list/) | การแทนที่แบบอักษรที่จะใช้เมื่อทำการแสดงผล<br/>            อ่าน/เขียน [`IFontSubstRuleCollection`](/slides/python-net/th/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/th/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | แสดงถึงชุดกฎ FontFallBack ของผู้ใช้สำหรับการจัดการชุดแบบอักษรเพื่อการแทนที่ที่เหมาะสมโดยใช้ฟังก์ชัน fallback<br/>            อ่าน/เขียน [`IFontFallBackRulesCollection`](/slides/python-net/th/aspose.slides/ifontfallbackrulescollection). |

## วิธีการ

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_substitutions/#) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ในการแสดงผลของงานนำเสนอ |
| [`get_substitutions(self, slides)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_substitutions/#listint) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ระหว่างการแสดงผลของสไลด์ที่ระบุ |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>            โปรดจำไว้เมื่อคัดลอกแบบอักษรใด ๆ เนื่องจากส่วนใหญ่มีลิขสิทธิ์ ก่อนอื่นให้ค้นหาใบอนุญาตของ <br/>            แบบอักษรก่อนและตรวจสอบว่ามีการย้ายไปยังเครื่องอื่นได้อย่างอิสระ สามารถโยน ArgumentException ได้หากข้อมูลแบบอักษรเป็น None หรือแบบอักษรนี้ถูกฝังไว้แล้ว |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>            โปรดจำไว้เมื่อเพิ่มแบบอักษรใด ๆ เนื่องจากส่วนใหญ่มีลิขสิทธิ์ ก่อนอื่นให้ค้นหาใบอนุญาตของ <br/>            แบบอักษรก่อนและตรวจสอบว่ามีการย้ายไปยังเครื่องอื่นได้อย่างอิสระ สามารถโยน ArgumentException ได้หากข้อมูลแบบอักษรเป็น None หรือแบบอักษรนี้ถูกฝังไว้แล้ว |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/th/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | แทนที่แบบอักษรในงานนำเสนอ |
| [`replace_font(self, subst_rule)`](/slides/python-net/th/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [`IFontSubstRule`](/slides/python-net/th/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/th/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในชุดของ [`IFontSubstRule`](/slides/python-net/th/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_fonts/#) | คืนค่าแบบอักษรที่ใช้ในงานนำเสนอ |
| [`get_embedded_fonts(self)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_embedded_fonts/#) | คืนค่าแบบอักษรที่ฝังไว้ในงานนำเสนอ |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/th/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | ลบแบบอักษรที่ฝังไว้ |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | ดึงอาเรย์ไบต์ที่แสดงข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่ระบุ |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | กำหนดระดับการฝังของแบบอักษรจากอาเรย์ไบต์และชื่อแบบอักษรที่ให้ |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)