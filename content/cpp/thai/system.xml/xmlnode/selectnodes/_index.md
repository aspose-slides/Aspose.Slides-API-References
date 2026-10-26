---
title: SelectNodes()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: เลือกรายการโหนดที่ตรงกับนิพจน์ XPath.
type: docs
weight: 365
url: /th/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) เมธอด

เลือกรายการโหนดที่ตรงกับนิพจน์ [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | นิพจน์ [XPath](../../../system.xml.xpath/). |

### ค่าที่ส่งคืน

อ็อบเจกต์ [XmlNodeList](../../xmlnodelist/) ที่มีคอลเลกชันของโหนดที่ตรงกับคำค้น [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) เมธอด

เลือกรายการโหนดที่ตรงกับนิพจน์ [XPath](../../../system.xml.xpath/). คำขึ้นต้นใด ๆ ที่พบในนิพจน์ [XPath](../../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../../xmlnamespacemanager/) ที่จัดหาให้.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | นิพจน์ [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) เพื่อใช้ในการแก้ไขเนมสเปซของคำขึ้นต้นในนิพจน์ [XPath](../../../system.xml.xpath/). |

### ค่าที่ส่งคืน

อ็อบเจกต์ [XmlNodeList](../../xmlnodelist/) ที่มีคอลเลกชันของโหนดที่ตรงกับคำค้น [XPath](../../../system.xml.xpath/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNodeList](../../xmlnodelist/)
* คลาส [String](../../../system/string/)
* คลาส [XmlNode](../)
* คลาส [XmlNamespaceManager](../../xmlnamespacemanager/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)