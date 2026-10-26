---
title: Deserialize()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงเอกสาร XML เป็นอ็อบเจ็กต์.
type: docs
weight: 14
url: /th/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) เมธอด


แปลง XML เอกสารเป็นอ็อบเจ็กต์

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Stream เพื่ออ่านเอกสารจาก |

### ค่าที่คืนกลับ

[Object](../../../system/object/) ที่เคยถูกทำการ serialize ไปในเอกสารที่ให้มา

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) เมธอด


แปลง XML เอกสารเป็นอ็อบเจ็กต์

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Reader เพื่ออ่านเอกสารจาก |

### ค่าที่คืนกลับ

[Object](../../../system/object/) ที่เคยถูกทำการ serialize ไปในเอกสารที่ให้มา

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) เมธอด


แปลง XML เอกสารเป็นอ็อบเจ็กต์

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader เพื่ออ่านเอกสารจาก |

### ค่าที่คืนกลับ

[Object](../../../system/object/) ที่เคยถูกทำการ serialize ไปในเอกสารที่ให้มา

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) เมธอด


แปลง XML เอกสารเป็นอ็อบเจ็กต์

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Reader เพื่ออ่านเอกสารจาก |
| encodingStyle | [String](../../../system/string/) | Style ที่ใช้ในการ serialize อ็อบเจ็กต์ |

### ค่าที่คืนกลับ

[Object](../../../system/object/) ที่เคยถูกทำการ serialize ไปในเอกสารที่ให้มา

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [XmlSerializer](../)
* คลาส [TextReader](../../../system.io/textreader/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::Serialization](../../)
* ไลบรารี [Aspose.Slides](../../../)