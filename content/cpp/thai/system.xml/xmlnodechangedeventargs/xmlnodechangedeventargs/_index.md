---
title: XmlNodeChangedEventArgs()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เริ่มต้นอินสแตนซ์ใหม่ของคลาส XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /th/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/) ที่สร้างเหตุการณ์ |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | พาเรนท์เก่า [XmlNode](../../xmlnode/) ของ [XmlNode](../../xmlnode/) ที่สร้างเหตุการณ์ |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | พาเรนท์ใหม่ [XmlNode](../../xmlnode/) ของ [XmlNode](../../xmlnode/) ที่สร้างเหตุการณ์ |
| oldValue | const [String](../../../system/string/)\& | ค่าตั้งเดิมของ [XmlNode](../../xmlnode/) ที่สร้างเหตุการณ์ |
| newValue | const [String](../../../system/string/)\& | ค่าใหม่ของ [XmlNode](../../xmlnode/) ที่สร้างเหตุการณ์ |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | ค่า XmlNodeChangedAction |

## ดูเพิ่มเติม

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)