---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Ketika dioverride dalam kelas turunan, mengambil nilai atribut dengan indeks yang ditentukan.
type: docs
weight: 612
url: /id/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) method


Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan indeks yang ditentukan.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | **int32_t** | Indeks atribut. |

### Nilai Kembali

Nilai atribut yang ditentukan.

## XmlReader::idx_get(String) method


Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan nilai [XmlReader::get_Name](../get_name/) yang ditentukan.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lengkap atribut. |

### Nilai Kembali

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan.

## XmlReader::idx_get(String, String) method


Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan nilai [XmlReader::get_LocalName](../get_localname/) dan [XmlReader::get_NamespaceURI](../get_namespaceuri/) yang ditentukan.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal atribut. |
| namespaceURI | [String](../../../system/string/) | URI namespace atribut. |

### Nilai Kembali

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)