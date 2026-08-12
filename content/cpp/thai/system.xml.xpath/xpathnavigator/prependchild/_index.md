---
title: PrependChild()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนอ็อบเจ็กต์ XmlWriter ที่ใช้สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบัน
type: docs
weight: 872
url: /th/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() เมธอด

ส่งคืนอ็อบเจ็กต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบัน

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบัน

## XPathNavigator::PrependChild(String) เมธอด

สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้สตริง XML ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | สตริงข้อมูล XML สำหรับโหนดลูกใหม่ |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) เมธอด

สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้เนื้อหา XML ของอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่ชี้ไปยังข้อมูล XML สำหรับโหนดลูกใหม่ |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) เมธอด

สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้โหนดในอ็อบเจ็กต์ [XPathNavigator](../) ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | อ็อบเจ็กต์ [XPathNavigator](../) ที่ชี้ไปยังโหนดที่จะเพิ่มเป็นโหนดลูกใหม่ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlWriter](../../../system.xml/xmlwriter/)
* คลาส [XPathNavigator](../)
* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* เนมสเปซ [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)