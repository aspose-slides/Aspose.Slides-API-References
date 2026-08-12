---
title: MoveTo()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เมื่อทำการเขียนทับในคลาสที่สืบทอด, จะย้าย XPathNavigator ไปยังตำแหน่งเดียวกับ XPathNavigator ที่ระบุ.
type: docs
weight: 664
url: /th/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) เมธอด

เมื่อทำการเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](../) ไปยังตำแหน่งเดียวกับ [XPathNavigator](../) ที่ระบุ.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | [XPathNavigator](../) ที่ตั้งอยู่บนโหนดที่คุณต้องการย้ายไป. |

### ค่าที่คืน

**true** หาก [XPathNavigator](../) การย้ายไปยังตำแหน่งเดียวกับ [XPathNavigator](../) ที่ระบุสำเร็จ; มิฉะนั้น, **false**. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)