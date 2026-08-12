---
title: get_Encoding()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าระดับการเข้ารหัสของเอกสาร XML.
type: docs
weight: 14
url: /th/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() เมธอด


คืนค่าระดับการเข้ารหัสของเอกสาร XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### ค่าที่ส่งกลับ

ชื่อการเข้ารหัสอักขระที่ถูกต้อง.
## หมายเหตุ



ชื่อการเข้ารหัสอักขระที่ได้รับการสนับสนุนบ่อยที่สุดสำหรับ XML มีดังต่อไปนี้: 

| หมวดหมู่ | ชื่อการเข้ารหัส |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |


ค่านี้เป็นค่าที่ไม่จำเป็นต้องกำหนด หากไม่ได้กำหนดค่า เมธอดนี้จะคืนค่า [String::Empty](../../../system/string/empty/). หากไม่มีแอตทริบิวต์การเข้ารหัสจะถือว่าใช้การเข้ารหัส UTF-8 เมื่อเอกสารถูกเขียนหรือบันทึกออก. 
## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlDeclaration](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)