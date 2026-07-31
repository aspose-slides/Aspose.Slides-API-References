---
title: GetElementsByTagName()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah XmlNodeList yang berisi daftar semua elemen keturunan yang cocok dengan nama yang ditentukan.
type: docs
weight: 443
url: /id/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) method

Mengembalikan sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua elemen keturunan yang cocok dengan nama yang ditentukan.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama terkwalifikasi untuk dicocokkan. Nilainya dicocokkan dengan nilai **get_Name** dari node yang cocok. Nilai khusus **\"*\"** mencocokkan semua tag. |

### Nilai Kembali

Sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua node yang cocok. Jika tidak ada node yang cocok dengan **name**, koleksi yang dikembalikan akan kosong.

## XmlDocument::GetElementsByTagName(String, String) method

Mengembalikan sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua elemen keturunan yang cocok dengan [XmlDocument::get_LocalName](../get_localname/) dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) yang ditentukan.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | LocalName yang akan dicocokkan. Nilai khusus **\"*\"** mencocokkan semua tag. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI yang akan dicocokkan. |

### Nilai Kembali

Sebuah [XmlNodeList](../../xmlnodelist/) yang berisi daftar semua node yang cocok. Jika tidak ada node yang cocok dengan **localName** dan **namespaceURI** yang ditentukan, koleksi yang dikembalikan akan kosong.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNodeList](../../xmlnodelist/)
* Kelas [String](../../../system/string/)
* Kelas [XmlDocument](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)