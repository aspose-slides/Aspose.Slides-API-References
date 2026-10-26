---
title: SetAttributeNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan XmlAttribute yang ditentukan.
type: docs
weight: 261
url: /id/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) metode

Menambahkan [XmlAttribute](../../xmlattribute/) yang ditentukan.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Node [XmlAttribute](../../xmlattribute/) yang akan ditambahkan ke koleksi atribut untuk elemen ini. |

### Nilai Kembali

Jika atribut menggantikan atribut yang sudah ada dengan nama yang sama, [XmlAttribute](../../xmlattribute/) lama dikembalikan; jika tidak, **nullptr** dikembalikan.

## XmlElement::SetAttributeNode(String, String) metode

Menambahkan [XmlAttribute](../../xmlattribute/) yang ditentukan.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal atribut. |
| namespaceURI | [String](../../../system/string/) | URI namespace atribut. |

### Nilai Kembali

[XmlAttribute](../../xmlattribute/) untuk ditambahkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlAttribute](../../xmlattribute/)
* Kelas [XmlElement](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)