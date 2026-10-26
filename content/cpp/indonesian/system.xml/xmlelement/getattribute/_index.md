---
title: GetAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai untuk atribut dengan nama yang ditentukan.
type: docs
weight: 209
url: /id/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) metode

Mengembalikan nilai untuk atribut dengan nama yang ditentukan.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama atribut yang akan diambil. Ini adalah nama yang memenuhi syarat. Itu dicocokkan dengan nilai **get_Name** dari node yang cocok. |

### Nilai Kembali

Nilai atribut yang ditentukan. String kosong dikembalikan jika atribut yang cocok tidak ditemukan atau jika atribut tidak memiliki nilai yang ditentukan atau nilai default.

## XmlElement::GetAttribute(String, String) metode

Mengembalikan nilai untuk atribut dengan nama lokal dan URI ruang nama yang ditentukan.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal atribut yang akan diambil. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama atribut yang akan diambil. |

### Nilai Kembali

Nilai atribut yang ditentukan. String kosong dikembalikan jika atribut yang cocok tidak ditemukan atau jika atribut tidak memiliki nilai yang ditentukan atau nilai default.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlElement](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)