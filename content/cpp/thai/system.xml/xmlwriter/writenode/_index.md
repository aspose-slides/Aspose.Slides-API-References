---
title: WriteNode()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อทำการ override ในคลาสที่สืบทอด, จะคัดลอกทุกอย่างจาก reader ไปยัง writer และย้าย reader ไปยังจุดเริ่มต้นของพี่น้องตัวต่อไป.
type: docs
weight: 430
url: /th/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) method

เมื่อทำการ override ในคลาสที่สืบทอด, จะคัดลอกทุกอย่างจาก reader ไปยัง writer และย้าย reader ไปยังตำแหน่งเริ่มต้นของพี่น้องตัวต่อไป.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) ที่จะอ่านจาก. |
| defattr | **bool** | **true** เพื่อคัดลอกแอตริบิวต์เริ่มต้นจาก [XmlReader](../../xmlreader/); หากไม่เป็นเช่นนั้น, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) method

คัดลอกทุกอย่างจากวัตถุ XPathNavigator ไปยัง writer. ตำแหน่งของ XPathNavigator ยังเหมือนเดิม.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | XPathNavigator ที่จะคัดลอกจาก. |
| defattr | **bool** | **true** เพื่อคัดลอกแอตริบิวต์เริ่มต้น; หากไม่เป็นเช่นนั้น, **false**. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)