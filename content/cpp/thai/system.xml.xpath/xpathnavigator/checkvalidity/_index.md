---
title: CheckValidity()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่า ข้อมูล XML ใน XPathNavigator สอดคล้องกับภาษาแบบจำเพาะ XML Schema (XSD) ที่ให้ไว้
type: docs
weight: 755
url: /th/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) เมธอด

ตรวจสอบว่า XML data ใน [XPathNavigator](../) สอดคล้องกับภาษาแบบจำเพาะ XML [Schema](../../../system.xml.schema/) (XSD) ที่ให้ไว้

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | XmlSchemaSet ที่มีสกีมาที่ใช้ในการตรวจสอบความถูกต้องของข้อมูล XML ที่อยู่ใน [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ValidationEventHandler ที่รับข้อมูลเกี่ยวกับคำเตือนและข้อผิดพลาดในการตรวจสอบสกีม่า. |

### ค่าที่คืนค่า

**true** หากไม่มีข้อผิดพลาดการตรวจสอบสกีม่า; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)