---
title: IBulletFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ibulletformat/
---
## IBulletFormat คลาส

แสดงคุณสมบัติการจัดรูปแบบหัวข้อย่อยของย่อหน้า

ประเภท IBulletFormat เปิดเผยสมาชิกต่อไปนี้:

## Properties

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/th/aspose.slides/ibulletformat/type/) | คืนค่า หรือกำหนดประเภทหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด.<br/>            อ่าน/เขียน [`BulletType`](/slides/python-net/th/aspose.slides/bullettype). |
| [`char`](/slides/python-net/th/aspose.slides/ibulletformat/char/) | คืนค่า หรือกำหนดอักขระหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด.<br/>            อ่าน/เขียน **System.Char**. |
| [`font`](/slides/python-net/th/aspose.slides/ibulletformat/font/) | คืนค่า หรือกำหนดแบบอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด.<br/>            อ่าน/เขียน [`IFontData`](/slides/python-net/th/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/th/aspose.slides/ibulletformat/height/) | คืนค่า หรือกำหนดความสูงของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด.<br/>            ค่า float.NaN กำหนดว่าหัวข้อย่อยสืบทอดความสูงจากส่วนแรกของย่อหน้า.<br/>            อ่าน/เขียน **float**. |
| [`color`](/slides/python-net/th/aspose.slides/ibulletformat/color/) | คืนค่ารูปแบบสีของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด.<br/>            อ่านอย่างเดียว [`IColorFormat`](/slides/python-net/th/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/th/aspose.slides/ibulletformat/picture/) | คืนค่าภาพที่ใช้เป็นหัวข้อย่อยในย่อหน้าที่ไม่มีการสืบทอด.<br/>            อ่านอย่างเดียว [`ISlidesPicture`](/slides/python-net/th/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/th/aspose.slides/ibulletformat/numbered_bullet_start_with/) | คืนค่า หรือกำหนดหมายเลขแรกที่ใช้สำหรับกลุ่มหัวข้อย่อยลำดับตัวเลขที่ไม่มีการสืบทอด.<br/>            อ่าน/เขียน **int**. |
| [`numbered_bullet_style`](/slides/python-net/th/aspose.slides/ibulletformat/numbered_bullet_style/) | คืนค่า หรือกำหนดลักษณะของหัวข้อย่อยลำดับตัวเลขที่ไม่มีการสืบทอด.<br/>            อ่าน/เขียน [`IBulletFormat.numbered_bullet_style`](/slides/python-net/th/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/th/aspose.slides/ibulletformat/is_bullet_hard_color/) | กำหนดว่าหัวข้อย่อยมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า.<br/>            **NullableBool.True**  ถ้าหัวข้อย่อยมีสีของตนเองและ **NullableBool.False**  หากหัวข้อย่อยสืบทอดสีจากส่วนแรกของย่อหน้า.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/th/aspose.slides/ibulletformat/is_bullet_hard_font/) | กำหนดว่าหัวข้อย่อยมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า.<br/>            **NullableBool.True**  ถ้าหัวข้อย่อยมีแบบอักษรของตนเองและ **NullableBool.False**  หากหัวข้อย่อยสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |

## Methods

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/th/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | กำหนดการเลื่อนค่าเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้งานหัวข้อย่อย (เช่น PowerPoint ทำเมื่อเปิดใช้งานหัวข้อย่อย/การนับลำดับในย่อหน้า). หากปิดใช้งานหัวข้อย่อยจะรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดการใช้งานหัวข้อย่อย/การนับลำดับในย่อหน้า). การเลื่อนค่า Indent จะนำไปใช้โดยอิงตามบริบทหัวข้อย่อยปัจจุบัน - IBulletFormat.Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก. การเลื่อนค่า Indent ที่ไม่เป็นศูนย์จะนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้าปัจจุบัน (ทำให้ค่าที่ได้เป็นค่าท้องถิ่น). |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides/ibulletformat/get_effective/#) | ดึงข้อมูลการจัดรูปแบบหัวข้อย่อยที่มีผลพร้อมการสืบทอดที่นำไปใช้. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)