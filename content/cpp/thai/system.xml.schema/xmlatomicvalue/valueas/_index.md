---
title: ValueAs()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็นค่าตามประเภทที่ระบุโดยใช้วัตถุ IXmlNamespaceResolver ที่ระบุเพื่อแก้ไขคำนำหน้าชื่อพื้นที่
type: docs
weight: 144
url: /th/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

คืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็นค่าตามประเภทที่ระบุโดยใช้วัตถุ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ระบุเพื่อแก้ไขคำนำหน้าชื่อพื้นที่

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทที่ใช้เพื่อคืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้ว |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) วัตถุที่ใช้เพื่อแก้ไขคำนำหน้าชื่อพื้นที่ |

### ค่าที่ส่งกลับ

ค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วตามประเภทที่ร้องขอ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* คลาส [XmlAtomicValue](../)
* เนมสเปซ [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)