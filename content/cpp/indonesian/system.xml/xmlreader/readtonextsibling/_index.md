---
title: ReadToNextSibling()
second_title: Referensi API Aspose.Slides untuk C++
description: Meneruskan XmlReader ke elemen saudara berikutnya dengan nama yang memenuhi syarat yang ditentukan.
type: docs
weight: 924
url: /id/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) method

Meneruskan [XmlReader](../) ke elemen saudara berikutnya dengan nama yang memenuhi syarat yang ditentukan.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lengkap elemen saudara yang ingin Anda pindahkan. |

### Return Value

**true** jika elemen saudara yang cocok ditemukan; selain itu **false**. Jika elemen saudara yang cocok tidak ditemukan, [XmlReader](../) diposisikan pada tag penutup (nilai [XmlReader::get_NodeType](../get_nodetype/) adalah [XmlNodeType::EndElement](../../xmlnodetype/)) dari elemen induk.

## XmlReader::ReadToNextSibling(String, String) method

Meneruskan [XmlReader](../) ke elemen saudara berikutnya dengan nama lokal dan URI namespace yang ditentukan.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal elemen saudara yang ingin Anda pindahkan. |
| namespaceURI | [String](../../../system/string/) | URI namespace elemen saudara yang ingin Anda pindahkan. |

### Return Value

**true** jika elemen saudara yang cocok ditemukan; selain itu **false**. Jika elemen saudara yang cocok tidak ditemukan, [XmlReader](../) diposisikan pada tag penutup (nilai [XmlReader::get_NodeType](../get_nodetype/) adalah [XmlNodeType::EndElement](../../xmlnodetype/)) dari elemen induk.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Namespace [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)