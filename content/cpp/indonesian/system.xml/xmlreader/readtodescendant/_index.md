---
title: ReadToDescendant()
second_title: Referensi API Aspose.Slides untuk C++
description: Meneruskan XmlReader ke elemen keturunan berikutnya dengan nama yang memenuhi syarat yang ditentukan.
type: docs
weight: 911
url: /id/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) method

Meneruskan [XmlReader](../) ke elemen keturunan berikutnya dengan nama yang memenuhi syarat.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama yang memenuhi syarat dari elemen yang ingin Anda pindahkan. |

### Nilai Kembali

**true** jika elemen keturunan yang cocok ditemukan; jika tidak **false**. Jika elemen anak yang cocok tidak ditemukan, [XmlReader](../) diposisikan pada tag penutup (nilai [XmlReader::get_NodeType](../get_nodetype/) adalah [XmlNodeType::EndElement](../../xmlnodetype/)) dari elemen tersebut. Jika [XmlReader](../) tidak diposisikan pada sebuah elemen ketika [XmlReader::ReadToDescendant(String)](./) dipanggil, metode ini mengembalikan **false** dan posisi [XmlReader](../) tidak berubah.

## XmlReader::ReadToDescendant(String, String) method

Meneruskan [XmlReader](../) ke elemen keturunan berikutnya dengan nama lokal dan URI ruang nama yang ditentukan.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal dari elemen yang ingin Anda pindahkan. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama dari elemen yang ingin Anda pindahkan. |

### Nilai Kembali

**true** jika elemen keturunan yang cocok ditemukan; jika tidak **false**. Jika elemen anak yang cocok tidak ditemukan, [XmlReader](../) diposisikan pada tag penutup (nilai [XmlReader::get_NodeType](../get_nodetype/) adalah [XmlNodeType::EndElement](../../xmlnodetype/)) dari elemen tersebut. Jika [XmlReader](../) tidak diposisikan pada sebuah elemen ketika [XmlReader::ReadToDescendant(String,String)](./) dipanggil, metode ini mengembalikan **false** dan posisi [XmlReader](../) tidak berubah.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)