---
title: Compile()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการคอมไพล์ XPath expression ที่ระบุและคืนอ็อบเจ็กต์ XPathExpression ที่เป็นตัวแทนของ XPath expression.
type: docs
weight: 66
url: /th/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) เมธอด

ทำการคอมไพล์ [XPath](../../) นิพจน์ที่ระบุและคืนค่าอ็อบเจ็กต์ [XPathExpression](../) ที่แสดงถึง [XPath](../../) นิพจน์.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | เป็น [XPath](../../) นิพจน์. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) เมธอด

ทำการคอมไพล์ [XPath](../../) นิพจน์ที่ระบุ, โดยใช้วัตถุ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ระบุสำหรับการแก้ปัญหา namespace, และคืนค่าอ็อบเจ็กต์ [XPathExpression](../) ที่แสดงถึง [XPath](../../) นิพจน์.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | เป็น [XPath](../../) นิพจน์. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | อ็อบเจ็กต์ที่ implements [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interface สำหรับการแก้ปัญหา namespace. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [XPathExpression](../).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathExpression](../)
* คลาส [String](../../../system/string/)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)