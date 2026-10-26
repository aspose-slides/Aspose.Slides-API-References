---
title: WriteStartElement()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride dalam kelas turunan, menulis tag pembuka yang ditentukan dan mengaitkannya dengan ruang nama yang diberikan.
type: docs
weight: 92
url: /id/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) metode


Saat dioverride dalam kelas turunan, menulis tag pembuka yang ditentukan dan mengaitkannya dengan ruang nama yang diberikan.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nama lokal elemen. |
| ns | const [String](../../../system/string/)\& | URI ruang nama untuk dikaitkan dengan elemen. Jika ruang nama ini sudah dalam lingkup dan memiliki prefiks yang terkait, penulis secara otomatis menulis prefiks tersebut juga. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) metode


Saat dioverride dalam kelas turunan, menulis tag pembuka yang ditentukan dan mengaitkannya dengan ruang nama dan prefiks yang diberikan.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks ruang nama elemen. |
| localName | const [String](../../../system/string/)\& | Nama lokal elemen. |
| ns | const [String](../../../system/string/)\& | URI ruang nama untuk dikaitkan dengan elemen. |

## XmlWriter::WriteStartElement(const String\&) metode


Saat dioverride dalam kelas turunan, menulis tag pembuka dengan nama lokal yang ditentukan.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nama lokal elemen. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlWriter](../)
* Ruang nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)