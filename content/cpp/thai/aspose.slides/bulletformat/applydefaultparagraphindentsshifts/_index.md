---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ตั้งค่าการเลื่อนค่าเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้งาน bullets (เช่น PowerPoint ทำเมื่อเปิดใช้งาน paragraph bullets/numbering ในโปรแกรม). หาก bullets ถูกปิดใช้งานก็จะรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดการใช้งาน paragraph bullets/numbering ในโปรแกรม). การเลื่อนค่า Indents จะถูกนำไปใช้โดยอ้างอิงบริบทของ bullet ปัจจุบัน - IBulletFormat::get(set)_Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก. การเลื่อนค่า indents ที่ไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้าปัจจุบัน (ทำให้ค่าที่ได้เป็นค่าท้องถิ่น)."
type: docs
weight: 235
url: /th/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() เมธอด


ตั้งค่าการเลื่อนค่าเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้งาน bullets (เช่น PowerPoint ทำเมื่อเปิดใช้งาน paragraph bullets/numbering ในมัน) หาก bullets ถูกปิดใช้งานแล้วจึงรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดใช้งาน paragraph bullets/numbering ในมัน) การเลื่อนค่า Indents จะถูกนำไปใช้โดยพิจารณาจากบริบทของ bullet ปัจจุบัน - IBulletFormat::get(set)_Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก การเลื่อนค่า indents ที่ไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้าปัจจุบัน (ทำให้ค่าที่ได้เป็นค่าในพื้นที่)

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```


## ดูเพิ่มเติม

* คลาส [BulletFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)