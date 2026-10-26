---
title: LookupPrefix()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เมื่อทำการ override ในคลาสที่สืบทอด จะคืนพรีฟิกซ์ที่ใกล้ที่สุดซึ่งกำหนดไว้ในสโคปเนมสเปซปัจจุบันสำหรับ URI ของเนมสเปซ
type: docs
weight: 352
url: /th/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) เมธอด


เมื่อทำการ override ในคลาสที่สืบทอด จะคืนพรีฟิกซ์ที่ใกล้ที่สุดที่กำหนดไว้ในสโคปเนมสเปซปัจจุบันสำหรับ URI ของเนมสเปซ

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ns | [String](../../../system/string/) | URI ของเนมสเปซที่คุณต้องการค้นหาพรีฟิกซ์ |

### ค่าที่ส่งกลับ

พรีฟิกซ์ที่ตรงกันหรือ **nullptr** หากไม่พบ URI ของเนมสเปซที่ตรงกันในสโคปปัจจุบัน

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlWriter](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)