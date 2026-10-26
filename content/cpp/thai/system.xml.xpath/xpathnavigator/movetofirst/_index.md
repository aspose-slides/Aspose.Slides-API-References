---
title: MoveToFirst()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ย้าย XPathNavigator ไปยังโหนดพี่น้องตัวแรกของโหนดปัจจุบัน.
type: docs
weight: 612
url: /th/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() method

ย้าย [XPathNavigator](../) ไปยังโหนดพี่น้องตัวแรกของโหนดปัจจุบัน.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) สำเร็จในการย้ายไปยังโหนดพี่น้องตัวแรกของโหนดปัจจุบัน; **false** หากไม่มีโหนดพี่น้องตัวแรก หรือหาก [XPathNavigator](../) กำลังอยู่ในตำแหน่งโหนดแอตทริบิวต์. หาก [XPathNavigator](../) อยู่ในตำแหน่งโหนดพี่น้องตัวแรกแล้ว, [XPathNavigator](../) จะคืนค่า **true** และจะไม่เปลี่ยนตำแหน่งของมัน. หาก [XPathNavigator::MoveToFirst](./) คืนค่า **false** เนื่องจากไม่มีโหนดพี่น้องตัวแรก, หรือหาก [XPathNavigator](../) กำลังอยู่ในตำแหน่งโหนดแอตทริบิวต์, ตำแหน่งของ [XPathNavigator](../) จะคงเดิม.

## ดูเพิ่มเติม

* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)