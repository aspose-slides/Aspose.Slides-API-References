---
title: GetAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai atribut dengan nama yang ditentukan.
type: docs
weight: 443
url: /id/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) method

Mengembalikan nilai atribut dengan nama yang ditentukan.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama terkualifikasi dari atribut. |

### Nilai Kembali

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan.

## XmlValidatingReader::GetAttribute(String, String) method

Mengembalikan nilai atribut dengan nama lokal dan Uniform Resource Identifier (URI) namespace yang ditentukan.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal dari atribut. |
| namespaceURI | [String](../../../system/string/) | URI namespace dari atribut. |

### Nilai Kembali

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan. Metode ini tidak memindahkan pembaca.

## XmlValidatingReader::GetAttribute(int32_t) method

Mengembalikan nilai atribut dengan indeks yang ditentukan.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | **int32_t** | Indeks atribut. Indeks dimulai dari nol. (Atribut pertama memiliki indeks 0.) |

### Nilai Kembali

Nilai atribut yang ditentukan.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlValidatingReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)