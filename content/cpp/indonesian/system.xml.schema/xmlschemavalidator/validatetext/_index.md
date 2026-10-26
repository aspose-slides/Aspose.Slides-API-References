---
title: ValidateText()
second_title: Referensi API Aspose.Slides untuk C++
description: Memvalidasi apakah string teks yang ditentukan diizinkan dalam konteks elemen saat ini, dan mengakumulasi teks untuk validasi jika elemen saat ini memiliki konten sederhana.
type: docs
weight: 183
url: /id/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) metode

Memvalidasi apakah **string** teks yang ditentukan diizinkan dalam konteks elemen saat ini, dan mengakumulasi teks untuk validasi jika elemen saat ini memiliki konten sederhana.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Sebuah **string** teks untuk divalidasi dalam konteks elemen saat ini. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) metode

Memvalidasi apakah teks yang dikembalikan oleh objek XmlValueGetter yang ditentukan diizinkan dalam konteks elemen saat ini, dan mengakumulasi teks untuk validasi jika elemen saat ini memiliki konten sederhana.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Callback XmlValueGetter yang digunakan untuk menyampaikan nilai teks sebagai tipe yang kompatibel dengan XML [Schema](../../) Definition Language (XSD) dari atribut. |

## Lihat Juga

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSchemaValidator](../)
* Ruang Nama [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)