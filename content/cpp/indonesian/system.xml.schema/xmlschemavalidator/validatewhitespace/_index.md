---
title: ValidateWhitespace()
second_title: Referensi API Aspose.Slides untuk C++
description: Memvalidasi apakah spasi putih dalam string yang ditentukan diizinkan dalam konteks elemen saat ini, dan mengakumulasi spasi putih untuk validasi jika elemen saat ini memiliki konten sederhana.
type: docs
weight: 196
url: /id/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) metode

Memvalidasi apakah spasi putih dalam **string** yang ditentukan diizinkan dalam konteks elemen saat ini, dan mengakumulasi spasi putih untuk validasi jika elemen saat ini memiliki konten sederhana.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Sebuah **string** spasi putih untuk divalidasi dalam konteks elemen saat ini. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) metode

Memvalidasi apakah spasi putih yang dikembalikan oleh objek XmlValueGetter yang ditentukan diizinkan dalam konteks elemen saat ini, dan mengakumulasi spasi putih untuk validasi jika elemen saat ini memiliki konten sederhana.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Sebuah callback XmlValueGetter yang digunakan untuk meneruskan nilai spasi putih sebagai tipe yang kompatibel dengan tipe Bahasa Definisi XML [Schema](../../) (XSD) atribut. |

## Lihat Juga

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSchemaValidator](../)
* Ruang nama [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)