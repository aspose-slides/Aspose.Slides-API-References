---
title: PreserveWhitespace()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อถูกแทนที่ในคลาสที่สืบทอด จะประเมินว่าควรรักษาโหนดช่องว่างหรือกำจัดออกในบริบทที่กำหนด
type: docs
weight: 40
url: /th/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) เมธอด

When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | โหนดช่องว่างที่ต้องการเก็บไว้หรือกำจัดออกในบริบทปัจจุบัน. |

### ค่าที่คืน

**true** หากต้องการเก็บช่องว่าง; **false** หากต้องการกำจัดช่องว่าง.

## ดูเพิ่มเติม

* typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* คลาส [XsltContext](../)
* เนมสเปซ [System::Xml::Xsl](../../)
* ไลบรารี [Aspose.Slides](../../../)