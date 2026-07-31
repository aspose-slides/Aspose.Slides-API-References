---
title: get_OldParent()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan nilai XmlNode::get_ParentNode sebelum operasi dimulai."
type: docs
weight: 27
url: /id/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() method

Mengembalikan nilai [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) sebelum operasi dimulai.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Nilai Kembalian

Nilai dari **ParentNode** sebelum operasi dimulai. Metode ini mengembalikan **nullptr** jika node tidak memiliki induk. Untuk node atribut, metode ini mengembalikan nilai [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)