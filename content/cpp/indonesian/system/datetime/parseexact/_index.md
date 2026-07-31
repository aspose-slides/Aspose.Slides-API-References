---
title: ParseExact()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek DateTime yang setara menggunakan format yang ditentukan dan informasi format yang spesifik budaya. Format representasi string harus cocok dengan format yang ditentukan secara tepat. Melemparkan pengecualian jika konversi gagal.
type: docs
weight: 872
url: /id/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metode


Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang setara menggunakan format yang ditentukan dan informasi format yang spesifik budaya. Format representasi string harus cocok dengan format yang ditentukan secara tepat. Melemparkan pengecualian jika konversi gagal.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |
| format | const [String](../../string/)\& | Format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format yang spesifik budaya. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Kombinasi bitwise dari nilai enumerasi yang memberikan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [DateTime](../). |

### Nilai Kembalian

Sebuah instance baru dari kelas [DateTime](../) yang mewakili nilai tanggal dan waktu yang setara dengan yang direpresentasikan oleh string yang ditentukan.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metode


Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang setara menggunakan format yang ditentukan, informasi format yang spesifik budaya, dan gaya. Format representasi string harus cocok dengan satu atau lebih format yang ditentukan secara tepat. Melemparkan pengecualian jika konversi gagal.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Array format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format yang spesifik budaya. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Kombinasi bitwise dari nilai enumerasi yang memberikan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [DateTime](../). |

### Nilai Kembalian

Sebuah instance baru dari kelas [DateTime](../) yang mewakili nilai tanggal dan waktu yang setara dengan yang direpresentasikan oleh string yang ditentukan.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [DateTime](../)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)