---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek DateTime yang setara.
type: docs
weight: 885
url: /id/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) metode

Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang setara.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |
| result | [DateTime](../)\& | Argumen keluaran yang, jika konversi berhasil, berisi hasil konversi. |

### Nilai Kembalian

True if conversion succeeds, otherwise - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metode

Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang setara menggunakan informasi format spesifik budaya dan gaya yang ditentukan.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format spesifik budaya. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Kombinasi bitwise dari nilai enumerasi yang menyediakan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [DateTime](../). |
| result | [DateTime](../)\& | Argumen keluaran yang, jika konversi berhasil, berisi hasil konversi. |

### Nilai Kembalian

True if conversion succeeds, otherwise - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metode




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metode




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metode




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [DateTime](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)