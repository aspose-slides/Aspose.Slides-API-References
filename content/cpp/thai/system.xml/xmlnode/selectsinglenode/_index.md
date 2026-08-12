---
title: SelectSingleNode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เลือก XmlNode แรกที่ตรงกับนิพจน์ XPath.
type: docs
weight: 352
url: /th/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) เมธอด


เลือก [XmlNode](../) แรกที่ตรงกับนิพจน์ [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | นิพจน์ [XPath](../../../system.xml.xpath/) |

### ค่าที่ส่งคืน

แรก [XmlNode](../) ที่ตรงกับคำค้น [XPath](../../../system.xml.xpath/) หรือ **nullptr** หากไม่พบโหนดที่ตรงกัน.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) เมธอด


เลือก [XmlNode](../) แรกที่ตรงกับนิพจน์ [XPath](../../../system.xml.xpath/). คำนำหน้าใด ๆ ที่พบในนิพจน์ [XPath](../../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../../xmlnamespacemanager/) ที่ให้มา.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | นิพจน์ [XPath](../../../system.xml.xpath/) |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ที่ใช้สำหรับแก้ไขเนมสเปซของคำนำหน้าในนิพจน์ [XPath](../../../system.xml.xpath/) |

### ค่าที่ส่งคืน

แรก [XmlNode](../) ที่ตรงกับคำค้น [XPath](../../../system.xml.xpath/) หรือ **nullptr** หากไม่พบโหนดที่ตรงกัน.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../)
* คลาส [String](../../../system/string/)
* คลาส [XmlNamespaceManager](../../xmlnamespacemanager/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)