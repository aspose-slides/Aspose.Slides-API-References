---
title: get_NewParent()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan nilai XmlNode::get_ParentNode setelah operasi selesai."
type: docs
weight: 40
url: /id/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() metode

Mengembalikan nilai [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) setelah operasi selesai.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### Nilai Kembali

Nilai **ParentNode** setelah operasi selesai. Metode ini mengembalikan **nullptr** jika node sedang dihapus. Untuk node atribut, metode ini mengembalikan nilai [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlNodeChangedEventArgs](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)