---
title: IFontsManager class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ifontsmanager/
---
## IFontsManager คลาส

จัดการแบบอักษรทั่วทั้งงานนำเสนอ.

ประเภท IFontsManager เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/th/aspose.slides/ifontsmanager/font_subst_rule_list/) | การแทนที่แบบอักษรที่ใช้เมื่อทำการแสดงผล<br/>อ่าน/เขียน [`IFontSubstRuleCollection`](/slides/python-net/th/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/th/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | เป็นตัวแทนของคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback<br/>อ่าน/เขียน [`IFontFallBackRulesCollection`](/slides/python-net/th/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/th/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | ระบุว่าแบบอักษรที่ลงทะเบียนควรได้รับการพิจารณาเหนือแบบอักษรที่ฝังอยู่ซึ่งมีชื่อและสไตล์แบบอักษรเดียวกันหรือไม่<br/>เมื่อเปิดใช้งาน แบบอักษรฝังที่ตรงกันจะถูกแทนที่ชั่วคราวด้วยแบบอักษรที่ลงทะเบียนที่สอดคล้องกันระหว่างการส่งออก. |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_substitutions/#) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ในการแสดงผลของงานนำเสนอ. |
| [`get_substitutions(self, slides)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_substitutions/#listint) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ระหว่างการแสดงผลของสไลด์ที่ระบุ. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>โปรดจำว่าเมื่อคัดลอกแบบอักษรใดๆ ส่วนใหญ่แบบอักษรมีลิขสิทธิ์ ก่อนอื่นค้นหาใบอนุญาตของ <br/>แบบอักษรและตรวจสอบว่ามันสามารถถ่ายโอนไปยังเครื่องอื่นได้อย่างอิสระ หากข้อมูลแบบอักษรเป็น None หรือแบบอักษรนี้ถูกฝังแล้วจะขว้าง ArgumentException |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/th/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | เพิ่มแบบอักษรที่ฝังไว้<br/>โปรดจำว่าเมื่อเพิ่มแบบอักษรใดๆ ส่วนใหญ่แบบอักษรมีลิขสิทธิ์ ก่อนองค์ค้นหาใบอนุญาตของ <br/>แบบอักษรและตรวจสอบว่ามันสามารถถ่ายโอนไปยังเครื่องอื่นได้อย่างอิสระ หากข้อมูลแบบอักษรเป็น None หรือแบบอักษรนี้ถูกฝังแล้วจะขว้าง ArgumentException |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/th/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | แทนที่แบบอักษรในงานนำเสนอ |
| [`replace_font(self, subst_rule)`](/slides/python-net/th/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [`IFontSubstRule`](/slides/python-net/th/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/th/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [`IFontSubstRule`](/slides/python-net/th/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_fonts/#) | ส่งคืนแบบอักษรที่ใช้ในงานนำเสนอ |
| [`get_embedded_fonts(self)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_embedded_fonts/#) | ส่งคืนแบบอักษรที่ฝังอยู่ในงานนำเสนอ |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/th/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | ลบแบบอักษรที่ฝังไว้ |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | ดึงอาร์เรย์ไบต์ที่แทนข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่ระบุ. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/th/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | กำหนดระดับการฝังแบบอักษรจากอาร์เรย์ไบต์และชื่อแบบอักษรที่ให้มา. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)