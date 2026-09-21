---
title: IParagraphFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iparagraphformat/
---
## IParagraphFormat คลาส

คลาสนี้ contains the paragraph formatting properties. Unlike [`IParagraphFormatEffectiveData`](/slides/python-net/th/aspose.slides/iparagraphformateffectivedata), all properties of this คลาส are writeable.

The IParagraphFormat type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`bullet`](/slides/python-net/th/aspose.slides/iparagraphformat/bullet/) | ส่งคืนรูปแบบสัญลักษณ์หัวข้อของย่อหน้า.<br/>            อ่านเท่านั้น [`IBulletFormat`](/slides/python-net/th/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/th/aspose.slides/iparagraphformat/depth/) | ส่งคืนหรือกำหนดความลึกของย่อหน้า.<br/>            ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด.<br/>            อ่าน/เขียน **int**. |
| [`alignment`](/slides/python-net/th/aspose.slides/iparagraphformat/alignment/) | ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด.<br/>            อ่าน/เขียน [`TextAlignment`](/slides/python-net/th/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/th/aspose.slides/iparagraphformat/space_within/) | ส่งคืนหรือกำหนดระยะห่างระหว่างบรรทัดฐานในย่อหน้า. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์, ค่าเป็นลบหมายถึงขนาดเป็นจุด. ไม่ได้ใช้การสืบทอด.<br/>            อ่าน/เขียน **float**. |
| [`space_before`](/slides/python-net/th/aspose.slides/iparagraphformat/space_before/) | ส่งคืนหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด.<br/>            ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ช่องว่างควรเป็น.<br/>            ค่าเป็นลบระบุขนาดของช่องว่างเป็นหน่วยจุด.<br/>            อ่าน/เขียน **float**. |
| [`space_after`](/slides/python-net/th/aspose.slides/iparagraphformat/space_after/) | ส่งคืนหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด.<br/>            ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ช่องว่างควรเป็น.<br/>            ค่าเป็นลบระบุขนาดของช่องว่างเป็นหน่วยจุด.<br/>            อ่าน/เขียน **float**. |
| [`east_asian_line_break`](/slides/python-net/th/aspose.slides/iparagraphformat/east_asian_line_break/) | กำหนดว่าจะใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/th/aspose.slides/iparagraphformat/right_to_left/) | กำหนดว่าจะใช้การเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/th/aspose.slides/iparagraphformat/latin_line_break/) | กำหนดว่าจะใช้การตัดบรรทัดแบบละตินในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/th/aspose.slides/iparagraphformat/hanging_punctuation/) | กำหนดว่าจะใช้เครื่องหมายวรรคตอนห้อยในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด.<br/>            อ่าน/เขียน [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/th/aspose.slides/iparagraphformat/margin_left/) | ส่งคืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด.<br/>            อ่าน/เขียน **float**. |
| [`margin_right`](/slides/python-net/th/aspose.slides/iparagraphformat/margin_right/) | ส่งคืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด.<br/>            อ่าน/เขียน **float**. |
| [`indent`](/slides/python-net/th/aspose.slides/iparagraphformat/indent/) | ส่งคืนหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. การเยื้องห้อยสามารถกำหนดด้วยค่าเป็นลบ.<br/>            อ่าน/เขียน **float**. |
| [`default_tab_size`](/slides/python-net/th/aspose.slides/iparagraphformat/default_tab_size/) | ส่งคืนหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด.<br/>            อ่าน/เขียน **float**. |
| [`tabs`](/slides/python-net/th/aspose.slides/iparagraphformat/tabs/) | ส่งคืนแท็บของย่อหน้า. ไม่ได้ใช้การสืบทอด.<br/>            อ่านเท่านั้น [`ITabCollection`](/slides/python-net/th/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/th/aspose.slides/iparagraphformat/font_alignment/) | ส่งคืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด.<br/>            อ่าน/เขียน [`FontAlignment`](/slides/python-net/th/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/th/aspose.slides/iparagraphformat/default_portion_format/) | ส่งคืนรูปแบบส่วนเริ่มต้นของย่อหน้า. ไม่ได้ใช้การสืบทอด.<br/>            อ่านเท่านั้น [`IPortionFormat`](/slides/python-net/th/aspose.slides/iportionformat). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides/iparagraphformat/get_effective/#) | รับข้อมูลการจัดรูปแบบย่อหน้าที่มีผลโดยใช้การสืบทอด |

### หมายเหตุ

คลาสนี้ใช้เพื่อส่งคืนและจัดการคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดสำหรับย่อหน้าที่เฉพาะเจาะจง. ซึ่งหมายความว่า
            ไม่ได้ใช้การสืบทอดเมื่อต้องการค่า ดังนั้นในหลาย ๆ กรณีคุณจะได้รับค่าที่หมายถึง "ไม่ได้กำหนด".

เพื่อรับค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [`IParagraphFormat.get_effective`](/slides/python-net/th/aspose.slides/iparagraphformat/get_effective) 
            ซึ่งส่งคืนอินสแตนซ์ [`IParagraphFormatEffectiveData`](/slides/python-net/th/aspose.slides/iparagraphformateffectivedata).

### ดูเพิ่มเติม
* คลาส [`IParagraphFormatEffectiveData`](/slides/python-net/th/aspose.slides/iparagraphformateffectivedata)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)