---
title: Read()
second_title: Aspose.Slides สำหรับ C++ - เอกสารอ้างอิง API
description: "อ่าน XML Schema จาก IO::TextReader ที่จัดหา"
type: docs
weight: 365
url: /th/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) เมธอด

อ่านไฟล์ XML [Schema](../../) จาก [IO::TextReader](../../../system.io/textreader/) ที่จัดหา

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | [IO::TextReader](../../../system.io/textreader/) ที่บรรจุ XML [Schema](../../) ที่จะอ่าน |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | ตัวจัดการเหตุการณ์การตรวจสอบที่รับข้อมูลเกี่ยวกับข้อผิดพลาดไวยากรณ์ XML [Schema](../../) |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XmlSchema](../) ที่แสดง XML [Schema](../../)

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) เมธอด

อ่านไฟล์ XML [Schema](../../) จากสตรีมที่จัดหา

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมข้อมูลที่จัดหา |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | ตัวจัดการเหตุการณ์การตรวจสอบที่รับข้อมูลเกี่ยวกับข้อผิดพลาดไวยากรณ์ XML [Schema](../../) |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XmlSchema](../) ที่แสดง XML [Schema](../../)

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) เมธอด

อ่าน XML [Schema](../../) จาก [XmlReader](../../../system.xml/xmlreader/) ที่จัดหา

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุ XML [Schema](../../) ที่จะอ่าน |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | ตัวจัดการเหตุการณ์การตรวจสอบที่รับข้อมูลเกี่ยวกับข้อผิดพลาดไวยากรณ์ XML [Schema](../../) |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XmlSchema](../) ที่แสดง XML [Schema](../../)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)