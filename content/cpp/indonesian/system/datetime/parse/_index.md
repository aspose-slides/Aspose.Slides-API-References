---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek DateTime yang setara.
type: docs
weight: 859
url: /id/system/datetime/parse/
---
## DateTime::Parse(const String\&) metode


Mengubah representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang setara.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |

### Nilai Kembalian

Sebuah instance baru dari kelas [DateTime](../) yang merepresentasikan nilai tanggal dan waktu yang setara dengan yang direpresentasikan oleh string yang ditentukan.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metode


Mengubah representasi string yang ditentukan dari nilai tanggal dan waktu menjadi objek [DateTime](../) yang setara menggunakan informasi format khusus budaya.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Representasi string dari nilai tanggal dan waktu yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format khusus budaya. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Kombinasi bitwise dari nilai enumerasi yang memberikan informasi tambahan tentang **s**, tentang elemen gaya yang mungkin ada dalam **s**, atau tentang konversi dari **s** ke objek [DateTime](../). |

### Nilai Kembalian

Sebuah instance baru dari kelas [DateTime](../) yang merepresentasikan nilai tanggal dan waktu yang setara dengan yang direpresentasikan oleh string yang ditentukan.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) metode




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)