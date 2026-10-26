---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string menjadi objek TimeSpan yang setara.
type: docs
weight: 534
url: /id/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) metode


Mengonversi string ke objek [TimeSpan](../) yang setara.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | String masukan. |

### Nilai Kembali

Interval waktu yang sesuai dengan string.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string ke objek [TimeSpan](../) yang setara menggunakan penyedia format yang ditentukan.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | String masukan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format yang menyediakan informasi pemformatan khusus budaya. |

### Nilai Kembali

Interval waktu yang sesuai dengan string.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) metode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [TimeSpan](../)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)