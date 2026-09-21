---
title: BaseSlide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/baseslide/
---
## BaseSlide คลาส

แสดงข้อมูลทั่วไปสำหรับประเภทสไลด์ทั้งหมด

ประเภท BaseSlide เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/th/aspose.slides/baseslide/shapes/) | คืนค่ารูปร่างของสไลด์หนึ่ง.<br/>            อ่านอย่างเดียว [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/th/aspose.slides/baseslide/controls/) | คืนค่าคอลเลกชันของควบคุม ActiveX บนสไลด์.<br/>            อ่านอย่างเดียว [`IControlCollection`](/slides/python-net/th/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/th/aspose.slides/baseslide/name/) | คืนค่าหรือกำหนดชื่อของสไลด์.<br/>            อ่าน/เขียน **str**. |
| [`slide_id`](/slides/python-net/th/aspose.slides/baseslide/slide_id/) | คืนค่า ID ของสไลด์.<br/>            อ่านอย่างเดียว **int**. |
| [`custom_data`](/slides/python-net/th/aspose.slides/baseslide/custom_data/) | คืนค่าข้อมูลที่กำหนดเองของสไลด์.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/th/aspose.slides/baseslide/timeline/) | คืนค่าอ็อบเจ็กต์ไทม์ไลน์ของแอนิเมชัน.<br/>            อ่านอย่างเดียว [`IAnimationTimeLine`](/slides/python-net/th/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/baseslide/slide_show_transition/) | คืนค่าอ็อบเจ็กต์ Transition ซึ่งบรรจุข้อมูลเกี่ยวกับ<br/>            วิธีที่สไลด์ที่กำหนดจะเคลื่อนที่ต่อในระหว่างการแสดงสไลด์.<br/>            อ่านอย่างเดียว [`ISlideShowTransition`](/slides/python-net/th/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/th/aspose.slides/baseslide/background/) | คืนค่าพื้นหลังของสไลด์.<br/>            อ่านอย่างเดียว [`IBackground`](/slides/python-net/th/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/baseslide/hyperlink_queries/) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่อยู่ในสไลด์ได้อย่างง่ายดาย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/baseslide/show_master_shapes/) | ระบุว่ารูปร่างบนมาสเตอร์สไลด์ควรแสดงบนสไลด์หรือไม่.<br/>            สำหรับมาสเตอร์สไลด์เองคุณสมบัตินี้จะคืนค่า `false` เสมอ.<br/>            อ่าน/เขียน **bool**. |
| [`presentation`](/slides/python-net/th/aspose.slides/baseslide/presentation/) | คืนค่าอินเทอร์เฟซ IPresentation.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/th/aspose.slides/baseslide/slide/) |  |

## วิธีการ

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/baseslide/join_portions_with_same_formatting/#) | รวม runs ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/th/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | รวม runs ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด. |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/baseslide/equals/#ibaseslide) | กำหนดว่าตัวอย่างสองออบเจ็กต์ IBaseSlide เท่ากันหรือไม่.<br/>            ค่าที่คืนคำนวณตามโครงสร้างของสไลด์และเนื้อหาคงที่.<br/>            สไลด์สองสไลด์เท่ากันหากรูปร่าง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ ทั้งหมดเท่ากัน. การเปรียบเทียบไม่คำนึงถึงค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าปัจจุบันของวันที่ใน Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/baseslide/create_theme_effective/#) | คืนค่าธีมที่มีผลสำหรับสไลด์นี้. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/baseslide/find_shape_by_alt_text/#str) | ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |

### ดูเพิ่มเติม
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)