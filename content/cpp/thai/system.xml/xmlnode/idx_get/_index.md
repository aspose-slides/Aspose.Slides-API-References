---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คืนค่า element ลูกตัวแรกที่มี XmlNode::get_Name ตามที่ระบุ."
type: docs
weight: 586
url: /th/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) method


คืนค่า element ลูกตัวแรกที่มี [XmlNode::get_Name](../get_name/) ตามที่ระบุ.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่ระบุอย่างสมบูรณ์ของ element ที่ต้องการดึง. |

### Return Value

[XmlElement](../../xmlelement/) ตัวแรกที่ตรงกับชื่อที่ระบุ. จะคืนค่า **nullptr** หากไม่มีการตรงกัน.

## XmlNode::idx_get(String, String) method


คืนค่า element ลูกตัวแรกที่มีค่า [XmlNode::get_LocalName](../get_localname/) และ [XmlNode::get_NamespaceURI](../get_namespaceuri/) ตามที่ระบุ.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | ชื่อท้องถิ่นของ element. |
| ns | [String](../../../system/string/) | URI ของ namespace ของ element. |

### Return Value

[XmlElement](../../xmlelement/) ตัวแรกที่ตรงกับ **localname** และ **ns**. จะคืนค่า **nullptr** หากไม่มีการตรงกัน.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlElement](../../xmlelement/)
* คลาส [String](../../../system/string/)
* คลาส [XmlNode](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)