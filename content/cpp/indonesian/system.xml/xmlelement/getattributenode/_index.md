---
title: GetAttributeNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan XmlAttribute dengan nama yang ditentukan.
type: docs
weight: 248
url: /id/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) metode

Mengembalikan [XmlAttribute](../../xmlattribute/) dengan nama yang ditentukan.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama atribut yang akan diambil. Ini adalah nama yang memenuhi syarat. Ini dicocokkan dengan nilai **get_Name** dari node yang cocok. |

### Nilai Kembali

[XmlAttribute](../../xmlattribute/) yang ditentukan atau **nullptr** jika atribut yang cocok tidak ditemukan.

## XmlElement::GetAttributeNode(String, String) metode

Mengembalikan [XmlAttribute](../../xmlattribute/) dengan nama lokal dan URI namespace yang ditentukan.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal atribut. |
| namespaceURI | [String](../../../system/string/) | URI namespace dari atribut. |

### Nilai Kembali

[XmlAttribute](../../xmlattribute/) yang ditentukan atau **nullptr** jika atribut yang cocok tidak ditemukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlAttribute](../../xmlattribute/)
* Kelas [String](../../../system/string/)
* Kelas [XmlElement](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)