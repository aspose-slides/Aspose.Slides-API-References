---
title: RemoveNamedItem()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ลบโหนดออกจาก XmlNamedNodeMap.
type: docs
weight: 40
url: /th/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) method

ลบโหนดออกจาก [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่มีคุณสมบัติครบถ้วนของโหนดที่ต้องการลบ ชื่อนี้จะเทียบกับค่า [XmlNode::get_Name](../../xmlnode/get_name/) ของโหนดที่ตรงกัน. |

### Return Value

[XmlNode](../../xmlnode/) ที่ลบจาก [XmlNamedNodeMap](../) นี้ หรือ **nullptr** หากไม่พบโหนดที่ตรงกัน.

## XmlNamedNodeMap::RemoveNamedItem(String, String) method

ลบโหนดที่มีค่า [XmlNode::get_LocalName](../../xmlnode/get_localname/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ตรงกัน.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดที่ต้องการลบ. |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของโหนดที่ต้องการลบ. |

### Return Value

[XmlNode](../../xmlnode/) ที่ลบ หรือ **nullptr** หากไม่พบโหนดที่ตรงกัน.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [String](../../../system/string/)
* คลาส [XmlNamedNodeMap](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)