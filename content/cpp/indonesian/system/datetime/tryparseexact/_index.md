---
title: TryParseExact()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek DateTime yang ekuivalen menggunakan format yang ditentukan, informasi format yang bersifat budaya, dan gaya. Format representasi string harus cocok secara tepat dengan format yang ditentukan.
type: docs
weight: 898
url: /id/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metode

Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang ekuivalen menggunakan format yang ditentukan, informasi format yang bersifat budaya, dan gaya. Format representasi string harus cocok dengan format yang ditentukan secara tepat.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |
| format | const [String](../../string/)\& | Format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format yang bersifat budaya. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Kombinasi bitwise dari nilai enumerasi yang menyediakan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [DateTime](../). |
| result | [DateTime](../)\& | Argumen output yang, jika konversi berhasil, berisi hasil konversi. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metode

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metode

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metode

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metode

Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang ekuivalen menggunakan format-format yang ditentukan, informasi format yang bersifat budaya, dan gaya. Format representasi string harus cocok dengan satu atau lebih format yang ditentukan secara tepat.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Array format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format yang bersifat budaya. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Kombinasi bitwise dari nilai enumerasi yang menyediakan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [DateTime](../). |
| result | [DateTime](../)\& | Argumen output yang, jika konversi berhasil, berisi hasil konversi. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metode

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metode

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metode

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [DateTime](../)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)