---
title: GetAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai atribut dengan nama yang ditentukan.
type: docs
weight: 287
url: /id/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) metode

Mengembalikan nilai atribut dengan nama yang ditentukan.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lengkap atribut. |

### Nilai Kembalian

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan.

## XmlNodeReader::GetAttribute(String, String) metode

Mengembalikan nilai atribut dengan nama lokal dan URI ruang nama yang ditentukan.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal atribut. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama atribut. |

### Nilai Kembalian

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan.

## XmlNodeReader::GetAttribute(int32_t) metode

Mengembalikan nilai atribut dengan indeks yang ditentukan.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| attributeIndex | **int32_t** | Indeks atribut. Indeks dimulai dari nol. (Atribut pertama memiliki indeks 0.) |

### Nilai Kembalian

Nilai atribut yang ditentukan.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNodeReader](../)
* RuangNama [System::Xml](../../)
* Library [Aspose.Slides](../../../)