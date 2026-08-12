---
title: InsertBefore()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนอ็อบเจ็กต์ XmlWriter ที่ใช้สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่ในปัจจุบัน.
type: docs
weight: 911
url: /th/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() เมธอด

ส่งคืนอ็อบเจ็กต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่ในปัจจุบัน

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่ในปัจจุบัน

## XPathNavigator::InsertBefore(String) เมธอด

สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่ในปัจจุบันโดยใช้สตริง XML ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | สตริงข้อมูล XML สำหรับโหนดพี่น้องใหม่ |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) เมธอด

สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่ในปัจจุบันโดยใช้เนื้อหา XML ของอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่อยู่บนข้อมูล XML สำหรับโหนดพี่น้องใหม่ |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) เมธอด

สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่ในปัจจุบันโดยใช้โหนดใน [XPathNavigator](../) ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | อ็อบเจ็กต์ [XPathNavigator](../) ที่อยู่บนโหนดที่จะเพิ่มเป็นโหนดพี่น้องใหม่ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlWriter](../../../system.xml/xmlwriter/)
* คลาส [XPathNavigator](../)
* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)