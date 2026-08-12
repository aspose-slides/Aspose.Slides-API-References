---
title: InsertAfter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนอ็อบเจ็กต์ XmlWriter ที่ใช้สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่ในขณะนี้.
type: docs
weight: 898
url: /th/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() เมธอด


ส่งคืนอ็อบเจ็กต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่ในขณะนี้.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```


### ค่าที่คืน

อ็อบเจ็กต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่ในขณะนี้.

## XPathNavigator::InsertAfter(String) เมธอด


สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่ในขณะนี้โดยใช้สตริง XML ที่ระบุ.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | สตริงข้อมูล XML สำหรับโหนดพี่น้องใหม่ |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) เมธอด


สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่ในขณะนี้โดยใช้เนื้อหา XML ของอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่ระบุ.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่ชี้ตำแหน่งไปยังข้อมูล XML สำหรับโหนดพี่น้องใหม่ |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) เมธอด


สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่ในขณะนี้โดยใช้โหนดในอ็อบเจ็กต์ [XPathNavigator](../) ที่ระบุ.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | อ็อบเจ็กต์ [XPathNavigator](../) ที่ชี้ตำแหน่งไปยังโหนดที่จะเพิ่มเป็นโหนดพี่น้องใหม่ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlWriter](../../../system.xml/xmlwriter/)
* คลาส [XPathNavigator](../)
* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)