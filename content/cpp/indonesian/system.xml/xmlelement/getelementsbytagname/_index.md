---
title: GetElementsByTagName()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan sebuah XmlNodeList yang berisi daftar semua elemen turunan yang cocok dengan XmlElement::get_Name yang ditentukan."
type: docs
weight: 287
url: /id/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) metode

Mengembalikan sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua elemen turunan yang cocok dengan [XmlElement::get_Name](../get_name/) yang ditentukan.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tag nama untuk dicocokkan. Ini adalah nama yang memenuhi syarat. Itu dicocokkan dengan nilai **get_Name** dari node yang cocok. Asterisk (*) adalah nilai khusus yang mencocokkan semua tag. |

### Nilai Kembalian

Sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua node yang cocok. Daftar kosong jika tidak ada node yang cocok.

## XmlElement::GetElementsByTagName(String, String) metode

Mengembalikan sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua elemen turunan yang cocok dengan nilai [XmlElement::get_LocalName](../get_localname/) dan [XmlElement::get_NamespaceURI](../get_namespaceuri/) yang ditentukan.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal untuk dicocokkan. Asterisk (*) adalah nilai khusus yang mencocokkan semua tag. |
| namespaceURI | [String](../../../system/string/) | URI namespace untuk dicocokkan. |

### Nilai Kembalian

Sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua node yang cocok. Daftar kosong jika tidak ada node yang cocok.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)