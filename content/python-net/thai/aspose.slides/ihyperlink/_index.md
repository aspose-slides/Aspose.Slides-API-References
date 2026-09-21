---
title: IHyperlink class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ihyperlink/
---
## IHyperlink คลาส

แสดงถึงไฮเปอร์ลิงก์.

ประเภท IHyperlink เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/th/aspose.slides/ihyperlink/action_type/) | ส่งคืนประเภทของการทำงานของ HyperLinkEx.<br/>            อ่านอย่างเดียว [`HyperlinkActionType`](/slides/python-net/th/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/th/aspose.slides/ihyperlink/external_url/) | ระบุ URL ภายนอก<br/>            หากคุณสมบัตินี้ไม่เป็นค่า None แล้วคุณสมบัติ TargetSlide จะเป็น None.<br/>            อ่านอย่างเดียว **str**. |
| [`external_url_original`](/slides/python-net/th/aspose.slides/ihyperlink/external_url_original/) | แสดงถึงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น.<br/>            <br/>            PowerPoint มีพฤติกรรมเฉพาะสำหรับลิงก์และข้อความที่สอดคล้องกันในส่วนหนึ่ง มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปแบบของ URL ที่ถูกต้อง ซึ่งแตกต่างจากที่อยู่จริงของลิงก์ ในกรณีนี้ เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข จะถูกเปลี่ยนให้ตรงกับส่วนของข้อความ คุณสมบัตินี้แสดงถึงค่าต้นฉบับของไฮเปอร์ลิงก์. |
| [`target_slide`](/slides/python-net/th/aspose.slides/ihyperlink/target_slide/) | หาก HyperlinkEx ชี้เป้าหมายไปยังสไลด์เฉพาะ จะส่งคืนสไลด์นี้.<br/>            หากคุณสมบัตินี้ไม่เป็นค่า None แล้วคุณสมบัติ ExternalUrl จะเป็น None.<br/>            อ่านอย่างเดียว [`ISlide`](/slides/python-net/th/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/th/aspose.slides/ihyperlink/target_frame/) | ส่งคืนเฟรมภายในชุดเฟรม HTML ของพาเรนท์สำหรับเป้าหมาย<br/>            ของไฮเปอร์ลิงก์พาเรนท์เมื่อมีอยู่.<br/>            อ่าน/เขียน **str**. |
| [`tooltip`](/slides/python-net/th/aspose.slides/ihyperlink/tooltip/) | ส่งคืนสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้<br/>            ที่เชื่อมโยงกับไฮเปอร์ลิงก์พाเรนท์.<br/>            อ่าน/เขียน **str**. |
| [`history`](/slides/python-net/th/aspose.slides/ihyperlink/history/) | กำหนดว่ามากเป้าหมายของไฮเปอร์ลิงก์พาเรนท์จะถูกเพิ่ม<br/>            ไปยังรายการไฮเปอร์ลิงก์ที่เคยดูเมื่อเรียกใช้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`highlight_click`](/slides/python-net/th/aspose.slides/ihyperlink/highlight_click/) | กำหนดว่าไฮเปอร์ลิงก์ควรเน้นเมื่อคลิกหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`stop_sound_on_click`](/slides/python-net/th/aspose.slides/ihyperlink/stop_sound_on_click/) | กำหนดว่าความเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`sound`](/slides/python-net/th/aspose.slides/ihyperlink/sound/) | แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์.<br/>            อ่าน/เขียน [`IAudio`](/slides/python-net/th/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/th/aspose.slides/ihyperlink/color_source/) | แสดงถึงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน.<br/>            อ่าน/เขียน [`HyperlinkColorSource`](/slides/python-net/th/aspose.slides/hyperlinkcolorsource). |

## วิธีการ

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/th/aspose.slides/ihyperlink/equals/#ihyperlink) | กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)