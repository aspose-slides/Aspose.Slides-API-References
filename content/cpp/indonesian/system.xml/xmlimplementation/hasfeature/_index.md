---
title: HasFeature()
second_title: Aspose.Slides untuk Referensi API C++
description: Menguji apakah implementasi Document Object Model (DOM) mendukung fitur tertentu.
type: docs
weight: 14
url: /id/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) metode

Menguji apakah Implementasi Model [Object](../../../system/object/) Dokumen (DOM) mendukung fitur tertentu.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Nama paket fitur yang akan diuji. Nama ini tidak sensitif huruf besar/kecil. |
| strVersion | const [String](../../../system/string/)\& | Ini adalah nomor versi dari nama paket yang akan diuji. Jika versi tidak ditentukan (**nullptr**), mendukung versi apa pun dari fitur tersebut menyebabkan metode mengembalikan **true**. |

### Nilai Kembali

**true** jika fitur diimplementasikan dalam versi yang ditentukan; jika tidak, **false**.

## Catatan

Tabel berikut menunjukkan kombinasi yang menyebabkan **HasFeature** mengembalikan **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlImplementation](../)
* RuangNama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)