---
title: AppendChild()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: คืนค่าอ็อบเจกต์ XmlWriter ที่ใช้สร้างโหนดลูกหนึ่งหรือหลายโหนดที่ตำแหน่งท้ายรายการของโหนดลูกของโหนดปัจจุบัน
type: docs
weight: 885
url: /th/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() เมธอด


คืนค่าอ็อบเจกต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดลูกหนึ่งหรือหลายโหนดที่ตำแหน่งท้ายรายการของโหนดลูกของโหนดปัจจุบัน

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### ค่าที่คืน

อ็อบเจกต์ [XmlWriter](../../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดลูกที่ตำแหน่งท้ายรายการของโหนดลูกของโหนดปัจจุบัน

## XPathNavigator::AppendChild(String) เมธอด


สร้างโหนดลูกใหม่ที่ตำแหน่งท้ายรายการของโหนดลูกของโหนดปัจจุบันโดยใช้สตริงข้อมูล XML ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | สตริงข้อมูล XML สำหรับโหนดลูกใหม่ |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) เมธอด


สร้างโหนดลูกใหม่ที่ตำแหน่งท้ายรายการของโหนดลูกของโหนดปัจจุบันโดยใช้เนื้อหา XML ของอ็อบเจกต์ [XmlReader](../../../system.xml/xmlreader/) ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | อ็อบเจกต์ [XmlReader](../../../system.xml/xmlreader/) ที่ชี้ตำแหน่งไปยังข้อมูล XML สำหรับโหนดลูกใหม่ |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) เมธอด


สร้างโหนดลูกใหม่ที่ตำแหน่งท้ายรายการของโหนดลูกของโหนดปัจจุบันโดยใช้โหนดใน [XPathNavigator](../) ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | อ็อบเจกต์ [XPathNavigator](../) ที่ชี้ตำแหน่งไปยังโหนดที่จะเพิ่มเป็นโหนดลูกใหม่ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)