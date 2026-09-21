---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
ตั้งค่าการชิดล่างเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ที่มีประสิทธิภาพของย่อหน้าเมื่อเปิดใช้งาน bullets (เช่น PowerPoint ทำเมื่อเปิดใช้งาน bullets/numbering ของย่อหน้า) หากปิดใช้งาน bullets จะรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดการใช้งาน bullets/numbering ของย่อหน้า) การชิดล่างของ Indents จะถูกนำไปใช้โดยอิงตามบริบทของ bullet ปัจจุบัน - IBulletFormat.Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก การชิดล่างที่ไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ของย่อหน้าปัจจุบัน (ทำให้ค่าผลลัพธ์เป็นค่าท้องถิ่น)

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | การเรียกใช้เมธอดนี้ไม่มีผลและจะทำให้เกิด **System.InvalidOperationException** ในกรณีต่อไปนี้:<br/>            ถ้าวัตถุที่จัดรูปแบบพาเร็นต์ไม่ใช่ย่อหน้า (เช่นการเรียก ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() จะทำให้เกิดข้อผิดพลาด);<br/>            หรือหากย่อหน้าไม่ได้ถูกเพิ่มเข้าไปในคอลเลกชัน ITextFrame.Paragraphs ใด ๆ (เพิ่มก่อน); |

### ดูเพิ่มเติม
* คลาส [`IBulletFormat`](/slides/python-net/th/aspose.slides/ibulletformat)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)