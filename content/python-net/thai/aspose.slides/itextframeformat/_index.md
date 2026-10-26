---
title: ITextFrameFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides/itextframeformat/
---
## ITextFrameFormat คลาส

ประกอบด้วยคุณสมบัติการจัดรูปแบบของ TextFrame

ประเภท ITextFrameFormat เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`text_style`](/slides/python-net/th/aspose.slides/itextframeformat/text_style/) | คืนค่ารูปแบบข้อความ.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/th/aspose.slides/itextframeformat/margin_left/) | คืนค่าหรือกำหนดระยะขอบซ้าย (points) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_right`](/slides/python-net/th/aspose.slides/itextframeformat/margin_right/) | คืนค่าหรือกำหนดระยะขอบขวา (points) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_top`](/slides/python-net/th/aspose.slides/itextframeformat/margin_top/) | คืนค่าหรือกำหนดระยะขอบบน (points) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_bottom`](/slides/python-net/th/aspose.slides/itextframeformat/margin_bottom/) | คืนค่าหรือกำหนดระยะขอบล่าง (points) ใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`wrap_text`](/slides/python-net/th/aspose.slides/itextframeformat/wrap_text/) | **True**  หากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/th/aspose.slides/itextframeformat/anchoring_type/) | คืนค่าหรือกำหนดข้อความยึดแนวตั้งใน TextFrame.<br/>            อ่าน/เขียน [`TextAnchorType`](/slides/python-net/th/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/th/aspose.slides/itextframeformat/center_text/) | หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/th/aspose.slides/itextframeformat/text_vertical_type/) | กำหนดการวางแนวข้อความ.<br/>            ค่าที่ได้ของการหมุนข้อความตามภาพสรุปจากคุณสมบัตินี้และมุมกำหนดเอง<br/>            ในคุณสมบัติ RotationAngle.<br/>            อ่าน/เขียน [`TextVerticalType`](/slides/python-net/th/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/th/aspose.slides/itextframeformat/autofit_type/) | คืนค่าหรือกำหนดโหมดการปรับขนาดอัตโนมัติของข้อความ.<br/>            อ่าน/เขียน [`TextAutofitType`](/slides/python-net/th/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/th/aspose.slides/itextframeformat/column_count/) | คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ.<br/>            ค่าดังกล่าวต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. <br/>            ค่า 0 หมายถึงค่าไม่กำหนด.<br/>            อ่าน/เขียน **int**. |
| [`column_spacing`](/slides/python-net/th/aspose.slides/itextframeformat/column_spacing/) | คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วย points). ควรใช้เมื่อมีคอลัมน์มากกว่า 1 คอลัมน์เท่านั้น.<br/>            ค่าดังกล่าวต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. <br/>            อ่าน/เขียน **float**. |
| [`three_d_format`](/slides/python-net/th/aspose.slides/itextframeformat/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่แสดงคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับข้อความ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/th/aspose.slides/itextframeformat/keep_text_flat/) | คืนค่าหรือกำหนดการทำให้ข้อความอยู่นอกฉาก 3D อย่างสมบูรณ์.<br/>            อ่าน/เขียน **bool**. |
| [`rotation_angle`](/slides/python-net/th/aspose.slides/itextframeformat/rotation_angle/) | ระบุการหมุนที่กำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต หากไม่ได้ระบุ การหมุนของรูปร่างที่แนบมาจะถูกใช้ หากระบุแล้ว จะถูกนำไปใช้แยกจากรูปร่าง คือรูปร่างอาจมีการหมุนเพิ่มเติมจากข้อความที่มีการหมุนของตนเอง.<br/>            ค่าที่ได้ของการหมุนข้อความตามภาพสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดล่วงหน้าในคุณสมบัติ TextVerticalType.<br/>            อ่าน/เขียน **float**. |
| [`transform`](/slides/python-net/th/aspose.slides/itextframeformat/transform/) | รับหรือกำหนดรูปร่างการตัดบรรทัดของข้อความ.<br/>            อ่าน/เขียน [`TextShapeType`](/slides/python-net/th/aspose.slides/textshapetype). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides/itextframeformat/get_effective/#) | รับข้อมูลการจัดรูปแบบ text frame ที่มีประสิทธิภาพพร้อมการสืบทอดที่ใช้. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)