---
title: get_Current()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อทำการเขียนทับในคลาสที่สืบทอด จะรับอ็อบเจ็กต์ XPathNavigator สำหรับ XPathNodeIterator นี้ ซึ่งกำหนดตำแหน่งบนโหนดบริบทปัจจุบัน.
type: docs
weight: 1
url: /th/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() เมธอด


เมื่อทำการเขียนทับในคลาสที่สืบทอด, จะรับอ็อบเจ็กต์ [XPathNavigator](../../xpathnavigator/) สำหรับ [XPathNodeIterator](../) นี้, ที่กำหนดตำแหน่งบนโหนดบริบทปัจจุบัน.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [XPathNavigator](../../xpathnavigator/) ที่กำหนดตำแหน่งบนโหนดบริบทที่ชุดโหนดถูกเลือก. ต้องเรียกใช้เมธอด [XPathNodeIterator::MoveNext](../movenext/) เพื่อย้าย [XPathNodeIterator](../) ไปยังโหนดแรกในชุดที่เลือก.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathNavigator](../../xpathnavigator/)
* คลาส [XPathNodeIterator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)