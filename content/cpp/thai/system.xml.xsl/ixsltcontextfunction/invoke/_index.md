---
title: Invoke()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ให้เมธอดสำหรับเรียกใช้งานฟังก์ชันด้วยอาร์กิวเมนต์ที่กำหนดในบริบทที่กำหนด
type: docs
weight: 53
url: /th/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) เมธอด

ให้เมธอดสำหรับเรียกใช้งานฟังก์ชันด้วยอาร์กิวเมนต์ที่กำหนดในบริบทที่กำหนด

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | บริบท XSLT สำหรับการเรียกใช้ฟังก์ชัน |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | อาร์กิวเมนต์ของการเรียกใช้ฟังก์ชัน แต่ละอาร์กิวเมนต์เป็นองค์ประกอบในอาเรย์ |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | โหนดบริบทสำหรับการเรียกใช้ฟังก์ชัน |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [Object](../../../system/object/) ที่เป็นตัวแทนของค่าที่ส่งคืนของฟังก์ชัน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)