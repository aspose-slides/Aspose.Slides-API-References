---
title: MoveToNext()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อถูกเขียนทับในคลาสที่สืบทอด จะย้าย XPathNavigator ไปยังโหนดพี่น้องถัดไปของโหนดปัจจุบัน.
type: docs
weight: 586
url: /th/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() เมธอด

เมื่อถูกเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](../) ไปยังโหนดพี่น้องถัดไปของโหนดปัจจุบัน.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### ค่าที่คืน

**true** หาก [XPathNavigator](../) ย้ายไปยังโหนดพี่น้องถัดไปสำเร็จ; มิฉะนั้น **false** หากไม่มีพี่น้องเหลือหรือหาก [XPathNavigator](../) อยู่ในโหนดแอตทริบิวต์ในขณะนี้. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## XPathNavigator::MoveToNext(String, String) เมธอด

ย้าย [XPathNavigator](../) ไปยังโหนดพี่น้องถัดไปที่มีชื่อท้องถิ่นและ URI เนมสเปซที่ระบุ.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดพี่น้องถัดไปที่ต้องการย้ายไป. |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของโหนดพี่น้องถัดไปที่ต้องการย้ายไป. |

### ค่าที่คืน

**true** หาก [XPathNavigator](../) ย้ายไปยังโหนดพี่น้องถัดไปสำเร็จ; **false** หากไม่มีพี่น้องเหลือหรือหาก [XPathNavigator](../) อยู่ในโหนดแอตทริบิวต์ในขณะนี้. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## XPathNavigator::MoveToNext(XPathNodeType) เมธอด

ย้าย [XPathNavigator](../) ไปยังโหนดพี่น้องถัดไปของโหนดปัจจุบันที่ตรงกับ XPathNodeType ที่ระบุ.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType ของโหนดพี่น้องที่ต้องการย้ายไป. |

### ค่าที่คืน

**true** หาก [XPathNavigator](../) ย้ายไปยังโหนดพี่น้องถัดไปสำเร็จ; มิฉะนั้น **false** หากไม่มีพี่น้องเหลือหรือหาก [XPathNavigator](../) อยู่ในโหนดแอตทริบิวต์ในขณะนี้. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## ดูเพิ่มเติม

* Enum [XPathNodeType](../../xpathnodetype/)
* คลาส [XPathNavigator](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)