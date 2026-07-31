---
title: ToDateTime()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi String menjadi ekivalen DateTime.
type: docs
weight: 417
url: /id/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) metode


Mengonversi [String](../../../system/string/) menjadi ekivalen [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | String yang akan dikonversi. |

### Nilai Kembalian

Sebuah ekivalen [DateTime](../../../system/datetime/) dari string.

## XmlConvert::ToDateTime(const String\&, const String\&) metode


Mengonversi [String](../../../system/string/) menjadi ekivalen [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | String yang akan dikonversi. |
| format | const [String](../../../system/string/)\& | Struktur format yang akan diterapkan pada [DateTime](../../../system/datetime/) yang telah dikonversi. Format yang valid meliputi "yyyy-MM-ddTHH:mm:sszzzzzz" dan subsetnya. String divalidasi terhadap format ini. |

### Nilai Kembalian

Sebuah ekivalen [DateTime](../../../system/datetime/) dari string.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) metode


Mengonversi [String](../../../system/string/) menjadi ekivalen [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | String yang akan dikonversi. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Array yang berisi struktur format yang akan diterapkan pada [DateTime](../../../system/datetime/) yang telah dikonversi. Format yang valid meliputi "yyyy-MM-ddTHH:mm:sszzzzzz" dan subsetnya. |

### Nilai Kembalian

Sebuah ekivalen [DateTime](../../../system/datetime/) dari string.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) metode


Mengonversi [String](../../../system/string/) menjadi [DateTime](../../../system/datetime/) menggunakan XmlDateTimeSerializationMode yang ditentukan.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Nilai [String](../../../system/string/) yang akan dikonversi. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Salah satu nilai enumerasi yang menentukan apakah tanggal harus dikonversi ke waktu lokal atau dipertahankan sebagai Coordinated Universal Time (UTC), jika itu merupakan tanggal UTC. |

### Nilai Kembalian

Sebuah ekivalen [DateTime](../../../system/datetime/) dari [String](../../../system/string/).

## Lihat Juga

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [DateTime](../../../system/datetime/)
* Kelas [String](../../../system/string/)
* Kelas [XmlConvert](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)