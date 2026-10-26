---
title: GetElementsByTagName()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ส่งคืน XmlNodeList ที่มีรายการขององค์ประกอบลูกทั้งหมดที่ตรงกับ XmlElement::get_Name ที่ระบุ."
type: docs
weight: 287
url: /th/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) เมธอด


ส่งคืน [XmlNodeList](../../xmlnodelist/) ที่มีรายการขององค์ประกอบลูกทั้งหมดที่ตรงกับ [XmlElement::get_Name](../get_name/) ที่ระบุ

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | แท็กชื่อที่ต้องการค้นหา ซึ่งเป็นชื่อที่มีการกำหนดคุณลักษณะ จะเปรียบเทียบกับค่า **get_Name** ของโหนดที่ตรงกัน เครื่องหมายดอกจัน (*) เป็นค่าพิเศษที่ตรงกับแท็กทั้งหมด |

### ค่าที่คืน

[XmlNodeList](../../xmlnodelist/) ที่มีรายการของโหนดที่ตรงกันทั้งหมด หากไม่มีโหนดที่ตรงกัน รายการจะว่างเปล่า

## XmlElement::GetElementsByTagName(String, String) เมธอด


ส่งคืน [XmlNodeList](../../xmlnodelist/) ที่มีรายการขององค์ประกอบลูกทั้งหมดที่ตรงกับค่าที่ระบุของ [XmlElement::get_LocalName](../get_localname/) และ [XmlElement::get_NamespaceURI](../get_namespaceuri/)

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นที่ต้องการค้นหา เครื่องหมายดอกจัน (*) เป็นค่าพิเศษที่ตรงกับแท็กทั้งหมด |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซที่ต้องการค้นหา |

### ค่าที่คืน

[XmlNodeList](../../xmlnodelist/) ที่มีรายการของโหนดที่ตรงกันทั้งหมด หากไม่มีโหนดที่ตรงกัน รายการจะว่างเปล่า

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNodeList](../../xmlnodelist/)
* คลาส [String](../../../system/string/)
* คลาส [XmlElement](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)