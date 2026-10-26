---
title: GetElementsByTagName()
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: ส่งคืน XmlNodeList ที่มีรายการของทุกองค์ประกอบลูกหลานที่ตรงกับชื่อที่ระบุ.
type: docs
weight: 443
url: /th/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) เมธอด

ส่งคืน [XmlNodeList](../../xmlnodelist/) ที่มีรายการของทุกองค์ประกอบลูกหลานที่ตรงกับชื่อที่ระบุ.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่มีคุณสมบัติครบถ้วนเพื่อใช้ในการจับคู่ จะถูกเปรียบเทียบกับค่า **get_Name** ของโหนดที่ตรงกัน ค่าเฉพาะ **\"*\"** จะตรงกับแท็กทั้งหมด |

### ค่าที่ส่งคืน

เป็น [XmlNodeList](../../xmlnodelist/) ที่มีรายการของทุกโหนดที่ตรงกัน หากไม่มีโหนดใดตรงกับ **name** คอลเลกชันที่ส่งคืนจะว่างเปล่า.

## XmlDocument::GetElementsByTagName(String, String) เมธอด

ส่งคืน [XmlNodeList](../../xmlnodelist/) ที่มีรายการของทุกองค์ประกอบลูกหลานที่ตรงกับ [XmlDocument::get_LocalName](../get_localname/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ที่ระบุ.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | LocalName เพื่อใช้ในการจับคู่ ค่าเฉพาะ **\"*\"** จะตรงกับแท็กทั้งหมด |
| namespaceURI | [String](../../../system/string/) | NamespaceURI เพื่อใช้ในการจับคู่ |

### ค่าที่ส่งคืน

เป็น [XmlNodeList](../../xmlnodelist/) ที่มีรายการของทุกโหนดที่ตรงกัน หากไม่มีโหนดใดตรงกับ **localName** และ **namespaceURI** คอลเลกชันที่ส่งคืนจะว่างเปล่า.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNodeList](../../xmlnodelist/)
* คลาส [String](../../../system/string/)
* คลาส [XmlDocument](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)