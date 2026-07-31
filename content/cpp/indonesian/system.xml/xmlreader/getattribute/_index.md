---
title: GetAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: "Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan nilai XmlReader::get_Name yang ditentukan."
type: docs
weight: 599
url: /id/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) metode

Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan nilai [XmlReader::get_Name](../get_name/) yang ditentukan.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama terkualifikasi dari atribut. |

### Nilai Kembalian

Nilai dari atribut yang ditentukan. Jika atribut tidak ditemukan atau nilainya [String::Empty](../../../system/string/empty/), **nullptr** dikembalikan.

## XmlReader::GetAttribute(String, String) metode

Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan nilai [XmlReader::get_LocalName](../get_localname/) dan [XmlReader::get_NamespaceURI](../get_namespaceuri/) yang ditentukan.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal dari atribut. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama dari atribut. |

### Nilai Kembalian

Nilai dari atribut yang ditentukan. Jika atribut tidak ditemukan atau nilainya [String::Empty](../../../system/string/empty/), **nullptr** dikembalikan. Metode ini tidak memindahkan pembaca.

## XmlReader::GetAttribute(int32_t) metode

Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan indeks yang ditentukan.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | **int32_t** | Indeks atribut. Indeks dimulai dari nol. (Atribut pertama memiliki indeks 0.) |

### Nilai Kembalian

Nilai dari atribut yang ditentukan. Metode ini tidak memindahkan pembaca.

## Lihat Juga

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)