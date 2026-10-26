---
title: Select()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เลือกชุดโหนดโดยใช้ XPath นิพจน์ที่ระบุ
type: docs
weight: 794
url: /th/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) เมธอด

เลือกชุดโหนดโดยใช้ [XPath](../../) นิพจน์ที่ระบุ

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | อ็อบเจกต์ [String](../../../system/string/) ที่แสดงถึง [XPath](../../) นิพจน์ |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XPathNodeIterator](../../xpathnodeiterator/) ที่ชี้ไปยังชุดโหนดที่เลือก

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

เลือกชุดโหนดโดยใช้ [XPath](../../) นิพจน์ที่ระบุพร้อมกับอ็อบเจกต์ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้ในการแก้ไขคำนำหน้าชื่อเนมสเปซ

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | อ็อบเจกต์ [String](../../../system/string/) ที่แสดงถึง [XPath](../../) นิพจน์ |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | อ็อบเจกต์ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้ในการแก้ไขคำนำหน้าชื่อเนมสเปซ |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XPathNodeIterator](../../xpathnodeiterator/) ที่ชี้ไปยังชุดโหนดที่เลือก

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) เมธอด

เลือกชุดโหนดโดยใช้ [XPathExpression](../../xpathexpression/) ที่ระบุ

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | อ็อบเจกต์ [XPathExpression](../../xpathexpression/) ที่มี [XPath](../../) คิวรีที่คอมไพล์แล้ว |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XPathNodeIterator](../../xpathnodeiterator/) ที่ชี้ไปยังชุดโหนดที่เลือก

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathNodeIterator](../../xpathnodeiterator/)
* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* คลาส [XPathExpression](../../xpathexpression/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)