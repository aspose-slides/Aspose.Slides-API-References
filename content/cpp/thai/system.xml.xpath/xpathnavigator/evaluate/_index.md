---
title: Evaluate()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ประเมินนิพจน์ XPath ที่ระบุและส่งคืนผลลัพธ์ที่มีประเภท
type: docs
weight: 807
url: /th/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) เมธอด

ประเมินนิพจน์ [XPath](../../) ที่ระบุและส่งคืนผลลัพธ์ที่มีชนิด

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | สตริงที่เป็นตัวแทนของนิพจน์ [XPath](../../) ที่สามารถประเมินได้ |

### ค่าที่คืน

ผลลัพธ์ของนิพจน์ ([Boolean](../../../system/boolean/), จำนวน, สตริง หรือ ชุดโหนด) นี้สอดคล้องกับอ็อบเจกต์ [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) หรือ [XPathNodeIterator](../../xpathnodeiterator/) ตามลำดับ

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

ประเมินนิพจน์ [XPath](../../) ที่ระบุและส่งคืนผลลัพธ์ที่มีชนิดโดยใช้วัตถุ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ระบุเพื่อแก้ไขคำนำหน้าชื่อเนมสเปซในนิพจน์ [XPath](../../)

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | สตริงที่เป็นตัวแทนของนิพจน์ [XPath](../../) ที่สามารถประเมินได้ |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | วัตถุ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้แก้ไขคำนำหน้าชื่อเนมสเปซในนิพจน์ [XPath](../../) |

### ค่าที่คืน

ผลลัพธ์ของนิพจน์ ([Boolean](../../../system/boolean/), จำนวน, สตริง หรือ ชุดโหนด) นี้สอดคล้องกับอ็อบเจกต์ [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) หรือ [XPathNodeIterator](../../xpathnodeiterator/) ตามลำดับ

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) เมธอด

ประเมิน [XPathExpression](../../xpathexpression/) และส่งคืนผลลัพธ์ที่มีชนิด

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) ที่สามารถประเมินได้ |

### ค่าที่คืน

ผลลัพธ์ของนิพจน์ ([Boolean](../../../system/boolean/), จำนวน, สตริง หรือ ชุดโหนด) นี้สอดคล้องกับอ็อบเจกต์ [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) หรือ [XPathNodeIterator](../../xpathnodeiterator/) ตามลำดับ

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) เมธอด

ใช้บริบทที่ให้มาเพื่อประเมิน [XPathExpression](../../xpathexpression/) และส่งคืนผลลัพธ์ที่มีชนิด

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) ที่สามารถประเมินได้ |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | [XPathNodeIterator](../../xpathnodeiterator/) ที่ชี้ไปยังชุดโหนดที่เลือกซึ่งการประเมินจะดำเนินการบน |

### ค่าที่คืน

ผลลัพธ์ของนิพจน์ ([Boolean](../../../system/boolean/), จำนวน, สตริง หรือ ชุดโหนด) นี้สอดคล้องกับอ็อบเจกต์ [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) หรือ [XPathNodeIterator](../../xpathnodeiterator/) ตามลำดับ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)