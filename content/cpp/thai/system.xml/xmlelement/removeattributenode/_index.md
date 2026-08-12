---
title: RemoveAttributeNode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบ XmlAttribute ที่ระบุ.
type: docs
weight: 274
url: /th/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) เมธอด


ลบ [XmlAttribute](../../xmlattribute/) ที่ระบุ.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | โนด [XmlAttribute](../../xmlattribute/) ที่จะลบ หากแอตทริบิวต์ที่ถูกลบมีค่าตั้งต้น จะถูกแทนที่โดยทันที. |

### Return Value

[XmlAttribute](../../xmlattribute/) ที่ถูกลบ หรือ **nullptr** หาก **oldAttr** ไม่ใช่โนดแอตทริบิวต์ของ [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) เมธอด


ลบ [XmlAttribute](../../xmlattribute/) ที่ระบุด้วยชื่อท้องถิ่นและ URI ของเนมสเปซ (หากแอตทริบิวต์ที่ถูกลบมีค่าตั้งต้น จะถูกแทนที่โดยทันที).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์. |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์. |

### Return Value

[XmlAttribute](../../xmlattribute/) ที่ถูกลบ หรือ **nullptr** หาก [XmlElement](../) ไม่มีโนดแอตทริบิวต์ที่ตรงกัน.

## See Also

* การนิยามชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlAttribute](../../xmlattribute/)
* คลาส [XmlElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)