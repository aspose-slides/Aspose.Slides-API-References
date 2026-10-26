---
title: Hyperlink class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/hyperlink/
---
## คลาส Hyperlink

เป็นการแทนไฮเปอร์ลิงก์หนึ่ง.

**การสืบทอด:**[`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)

ประเภท Hyperlink มีสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/th/aspose.slides/hyperlink/__init__/#str) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์หนึ่ง. |
| [`__init__(self, slide)`](/slides/python-net/th/aspose.slides/hyperlink/__init__/#islide) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์ที่ระบุ.<br/>            หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับวัตถุใดวัตถุหนึ่งจากการนำเสนอเดียวกัน มิฉะนั้นลิงก์จะถูกบันทึกเป็น NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/th/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นต้นทาง, แทนที่คุณสมบัติรอง. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`no_action`](/slides/python-net/th/aspose.slides/hyperlink/no_action/) | คืนค่าไฮเปอร์ลิงก์พิเศษ "do nothing".<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/th/aspose.slides/hyperlink/media/) | คืนค่าไฮเปอร์ลิงก์พิเศษ "play mediafile". ใช้ใน AudioFrame และ VideoFrame.<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/th/aspose.slides/hyperlink/next_slide/) | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป.<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/th/aspose.slides/hyperlink/previous_slide/) | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า.<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/th/aspose.slides/hyperlink/first_slide/) | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์แรกของการนำเสนอ.<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/th/aspose.slides/hyperlink/last_slide/) | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของการนำเสนอ.<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/th/aspose.slides/hyperlink/last_vieved_slide/) | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด.<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/th/aspose.slides/hyperlink/end_show/) | คืนค่าไฮเปอร์ลิงก์ที่หยุดการแสดง.<br/>            อ่านอย่างเดียว [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/th/aspose.slides/hyperlink/action_type/) | คืนค่าประเภทของการกระทำของ Hyperlink.<br/>            อ่านอย่างเดียว [`HyperlinkActionType`](/slides/python-net/th/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/th/aspose.slides/hyperlink/external_url/) | ระบุ URL ภายนอก.<br/>            อ่านอย่างเดียว **str**. |
| [`target_slide`](/slides/python-net/th/aspose.slides/hyperlink/target_slide/) | หาก Hyperlink ชี้ไปยังสไลด์เฉพาะ จะคืนค่าสไลด์นั้น.<br/>            อ่านอย่างเดียว [`ISlide`](/slides/python-net/th/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/th/aspose.slides/hyperlink/external_url_original/) | เป็นไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น.<br/>            <br/>            PowerPoint มีการทำงานเฉพาะสำหรับลิงก์และข้อความที่สอดคล้องกันในส่วนนั้น. มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปแบบของ URL ที่ถูกต้อง, ซึ่งแตกต่างจากที่อยู่จริงของลิงก์. ในกรณีนี้, เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข, จะถูกเปลี่ยนให้ตรงกับส่วนข้อความ. คุณสมบัตินี้แทนค่าต้นฉบับของไฮเปอร์ลิงก์. |
| [`target_frame`](/slides/python-net/th/aspose.slides/hyperlink/target_frame/) | คืนค่าเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมาย<br/>            ของไฮเปอร์ลิงก์พาเรนท์เมื่อมีอยู่.<br/>            อ่าน/เขียน **str**. |
| [`tooltip`](/slides/python-net/th/aspose.slides/hyperlink/tooltip/) | คืนค่าสตริงที่อาจปรากฏในส่วนติดต่อผู้ใช้<br/>            ที่สัมพันธ์กับไฮเปอร์ลิงก์พาเรนท์.<br/>            อ่าน/เขียน **str**. |
| [`history`](/slides/python-net/th/aspose.slides/hyperlink/history/) | กำหนดว่าตัวเป้าหมายของไฮเปอร์ลิงก์พาเรนท์จะถูกเพิ่ม<br/>            ไปยังรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`highlight_click`](/slides/python-net/th/aspose.slides/hyperlink/highlight_click/) | กำหนดว่าไฮเปอร์ลิงก์ควรจะไฮไลต์เมื่อคลิกหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`stop_sound_on_click`](/slides/python-net/th/aspose.slides/hyperlink/stop_sound_on_click/) | กำหนดว่าควรหยุดเสียงเมื่อคลิกไฮเปอร์ลิงก์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`sound`](/slides/python-net/th/aspose.slides/hyperlink/sound/) | เป็นเสียงที่กำลังเล่นของไฮเปอร์ลิงก์.<br/>            อ่าน/เขียน [`IAudio`](/slides/python-net/th/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/th/aspose.slides/hyperlink/color_source/) | เป็นแหล่งของสีไฮเปอร์ลิงก์ - ไม่ว่าจะเป็นสไตล์หรือรูปแบบส่วน.<br/>            อ่าน/เขียน [`HyperlinkColorSource`](/slides/python-net/th/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/th/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/hyperlink/presentation/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/th/aspose.slides/hyperlink/equals/#ihyperlink) | กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่. |

### ดูเพิ่มเติม
* คลาส [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink)
* คลาส [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)