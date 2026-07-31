---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides untuk Referensi API C++
description: Menginisialisasi sebuah instance baru dari kelas XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /id/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor


Menginisialisasi sebuah instance baru dari kelas [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/) yang menghasilkan peristiwa. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Induk lama [XmlNode](../../xmlnode/) dari [XmlNode](../../xmlnode/) yang menghasilkan peristiwa. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Induk baru [XmlNode](../../xmlnode/) dari [XmlNode](../../xmlnode/) yang menghasilkan peristiwa. |
| oldValue | const [String](../../../system/string/)\& | Nilai lama dari [XmlNode](../../xmlnode/) yang menghasilkan peristiwa. |
| newValue | const [String](../../../system/string/)\& | Nilai baru dari [XmlNode](../../xmlnode/) yang menghasilkan peristiwa. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction. |

## Lihat Juga

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [String](../../../system/string/)
* Kelas [XmlNodeChangedEventArgs](../)
* Ruang nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)