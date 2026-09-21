---
title: TextFrameFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/textframeformat/
---
## TextFrameFormat คลาส

ประกอบด้วยคุณสมบัติ formatTextFrameFormatting ของ TextFrame.

**สืบทอด:**[`TextFrameFormat`](/slides/python-net/th/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)

ประเภท TextFrameFormat เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/textframeformat/__init__/#) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [`TextFrameFormat`](/slides/python-net/th/aspose.slides/textframeformat). |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`three_d_format`](/slides/python-net/th/aspose.slides/textframeformat/three_d_format/) | คืนค่าอ็อบเจกต์ ThreeDFormat ที่แสดงคุณสมบัติผลกระทบ 3D สำหรับข้อความ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/th/aspose.slides/textframeformat/margin_left/) | คืนค่า หรือ ตั้งค่าขอบซ้าย (จุด) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_right`](/slides/python-net/th/aspose.slides/textframeformat/margin_right/) | คืนค่า หรือ ตั้งค่าขอบขวา (จุด) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_top`](/slides/python-net/th/aspose.slides/textframeformat/margin_top/) | คืนค่า หรือ ตั้งค่าขอบบน (จุด) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_bottom`](/slides/python-net/th/aspose.slides/textframeformat/margin_bottom/) | คืนค่า หรือ ตั้งค่าขอบล่าง (จุด) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`wrap_text`](/slides/python-net/th/aspose.slides/textframeformat/wrap_text/) | **True** หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/th/aspose.slides/textframeformat/anchoring_type/) | คืนค่า หรือ ตั้งค่าแนวตั้งของข้อความใน TextFrame.<br/>            อ่าน/เขียน [`TextAnchorType`](/slides/python-net/th/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/th/aspose.slides/textframeformat/center_text/) | หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/th/aspose.slides/textframeformat/text_vertical_type/) | กำหนดทิศทางของข้อความ.<br/>            ค่าที่ได้จากการหมุนของข้อความสรุปจากคุณสมบัตินี้และมุมที่กำหนดเองในคุณสมบัติ RotationAngle.<br/>            อ่าน/เขียน [`TextVerticalType`](/slides/python-net/th/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/th/aspose.slides/textframeformat/autofit_type/) | คืนค่า หรือ ตั้งค่าโหมดการปรับขนาดอัตโนมัติของข้อความ.<br/>            อ่าน/เขียน [`TextAutofitType`](/slides/python-net/th/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/th/aspose.slides/textframeformat/column_count/) | คืนค่า หรือ ตั้งค่าจำนวนคอลัมน์ในพื้นที่ข้อความ.<br/>            ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. <br/>            ค่า 0 หมายถึงค่าที่ไม่กำหนด.<br/>            อ่าน/เขียน **int**. |
| [`column_spacing`](/slides/python-net/th/aspose.slides/textframeformat/column_spacing/) | คืนค่า หรือ ตั้งค่าระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด) โดยควรใช้เมื่อตรงนี้มีมากกว่าหนึ่งคอลัมน์.<br/>            ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. <br/>            อ่าน/เขียน **float**. |
| [`rotation_angle`](/slides/python-net/th/aspose.slides/textframeformat/rotation_angle/) | กำหนดการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกล่อง จำกัด หากไม่ได้กำหนดจะใช้การหมุนของรูปร่างที่แนบ.<br/>            หากกำหนดแล้วจะถูกใช้แยกจากรูปร่างซึ่งรูปร่างอาจมีการหมุนเพิ่มเติมจากข้อความ.<br/>            ค่าที่ได้จากการหมุนของข้อความสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType.<br/>            อ่าน/เขียน **float**. |
| [`transform`](/slides/python-net/th/aspose.slides/textframeformat/transform/) | รับหรือตั้งค่ารูปร่างการพันข้อความ.<br/>            อ่าน/เขียน [`TextShapeType`](/slides/python-net/th/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/th/aspose.slides/textframeformat/keep_text_flat/) | รับหรือตั้งค่าให้ข้อความอยู่แบนแม้จะมีผลกระทบการหมุน 3-D.<br/>            อ่าน/เขียน **bool**. |
| [`slide`](/slides/python-net/th/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/th/aspose.slides/textframeformat/text_style/) |  |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides/textframeformat/get_effective/#) | รับข้อมูลการจัดรูปแบบ text frame อย่างมีประสิทธิภาพพร้อมการสืบทอดที่นำไปใช้. |

### ดูเพิ่มเติม
* คลาส [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)
* คลาส [`TextFrameFormat`](/slides/python-net/th/aspose.slides/textframeformat)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)