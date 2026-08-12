---
title: XPathNodeType
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดประเภทโหนด XPath ที่สามารถส่งคืนได้จากคลาส XPathNavigator
type: docs
weight: 157
url: /th/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

กำหนดประเภทโหนด [XPath](../) ที่สามารถส่งกลับได้จากคลาส [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Root | 0 | โหนดรากของเอกสาร XML หรือโหนดต้นไม้ |
| Element | 1 | อีลีเมนต์หนึ่ง, เช่น **<element>** |
| Attribute | 2 | แอตทริบิวต์หนึ่ง, เช่น **id='123'** |
| Namespace | 3 | เนมสเปซหนึ่ง, เช่น **xmlns=\"namespace\"** |
| Text | 4 | เนื้อหาข้อความของโหนด. เทียบเท่ากับ Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) และประเภทโหนด CDATA. มีอย่างน้อยหนึ่งอักขระ |
| SignificantWhitespace | 5 | โหนดที่มีอักขระช่องว่างและ **xml:space** ถูกตั้งค่าเป็น **preserve** |
| Whitespace | 6 | โหนดที่มีเพียงอักขระช่องว่างและไม่มีช่องว่างที่สำคัญ. อักขระช่องว่างคือ **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'** |
| ProcessingInstruction | 7 | คำสั่งประมวลผล, เช่น **<?pi test?>**. สิ่งนี้ไม่รวมการประกาศ XML, ซึ่งไม่ปรากฏต่อคลาส [XPathNavigator](../xpathnavigator/) |
| Comment | 8 | คอมเมนต์หนึ่ง, เช่น **** |
| All | 9 | ประเภทโหนด XPathNodeType ใดก็ได้ |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml::XPath](../)
* ไลบรารี [Aspose.Slides](../../)