---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
กำหนดการเลื่อนค่าเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้งาน bullet (เช่น PowerPoint ทำเมื่อเปิดใช้งาน bullet/การตั้งหมายเลขในย่อหน้า) หากปิดใช้งาน bullet แล้วจะรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดการใช้งาน bullet/การตั้งหมายเลขในย่อหน้า) การเลื่อนค่า Indent จะถูกนำไปใช้โดยพิจารณาจากบริบทของ bullet ปัจจุบัน – IBulletFormat.Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก การเลื่อนค่า Indent ที่ไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้าปัจจุบัน (ทำให้ค่าที่ได้เป็นค่าท้องถิ่น)


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | การเรียกใช้เมธอดนี้ไม่มีผลและจะทำให้เกิด **System.InvalidOperationException** ในกรณีต่อไปนี้:<br/>            หากวัตถุที่ฟอร์แมตโดยพ่อแม่ไม่ใช่ย่อหน้า (เช่น การเรียก ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() จะทำให้เกิดข้อยกเว้น);<br/>            หรือหากย่อหน้าไม่ได้ถูกเพิ่มเข้าไปในคอลเลกชัน ITextFrame.Paragraphs ใด ๆ (เพิ่มย่อหน้าก่อน); |



### See Also
* class [`BulletFormat`](/slides/python-net/th/aspose.slides/bulletformat)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)