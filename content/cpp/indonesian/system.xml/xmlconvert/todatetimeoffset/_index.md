---
title: ToDateTimeOffset()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengonversi String yang diberikan menjadi ekivalen DateTimeOffset.
type: docs
weight: 430
url: /id/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) metode


Mengonversi [String](../../../system/string/) yang diberikan menjadi ekivalen [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | String yang akan dikonversi. String harus sesuai dengan subset dari Rekomendasi W3C untuk tipe XML dateTime. Untuk informasi lebih lanjut, lihat bagian [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) dari spesifikasi XML [Schema](../../../system.xml.schema/). |

### Nilai Kembalian

Ekivalen [DateTimeOffset](../../../system/datetimeoffset/) dari string yang diberikan.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) metode


Mengonversi [String](../../../system/string/) yang diberikan menjadi ekivalen [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | String yang akan dikonversi. |
| format | const [String](../../../system/string/)\& | Format yang digunakan untuk mengonversi **s**. Parameter format dapat berupa subset apa pun dari Rekomendasi W3C untuk tipe XML dateTime. Untuk informasi lebih lanjut, lihat bagian [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) dari spesifikasi XML [Schema](../../../system.xml.schema/). String **s** divalidasi terhadap format ini. |

### Nilai Kembalian

Ekivalen [DateTimeOffset](../../../system/datetimeoffset/) dari string yang diberikan.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) metode


Mengonversi [String](../../../system/string/) yang diberikan menjadi ekivalen [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | String yang akan dikonversi. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Sekumpulan format yang dapat digunakan untuk mengonversi **s**. Setiap format dalam **formats** dapat berupa subset apa pun dari Rekomendasi W3C untuk tipe XML dateTime. Untuk informasi lebih lanjut, lihat bagian [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) dari spesifikasi XML [Schema](../../../system.xml.schema/). String **s** divalidasi terhadap salah satu format ini. |

### Nilai Kembalian

Ekivalen [DateTimeOffset](../../../system/datetimeoffset/) dari string yang diberikan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [DateTimeOffset](../../../system/datetimeoffset/)
* Kelas [String](../../../system/string/)
* Kelas [XmlConvert](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)