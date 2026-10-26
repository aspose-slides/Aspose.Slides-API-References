---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string menjadi objek TimeSpan yang setara dan mengembalikan hasil konversi.
type: docs
weight: 560
url: /id/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) metode


Mengonversi string menjadi objek [TimeSpan](../) yang setara dan mengembalikan hasil konversi.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | String masukan. |
| result | [TimeSpan](../)\& | Interval waktu yang sesuai dengan string. |

### Return Value

True jika string berhasil dikonversi; selain itu, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metode


Mengonversi string menjadi objek [TimeSpan](../) yang setara menggunakan penyedia format yang ditentukan dan mengembalikan hasil konversi.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | String masukan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format yang menyediakan informasi pemformatan khusus budaya. |
| result | [TimeSpan](../)\& | Interval waktu yang sesuai dengan string. |

### Return Value

True jika string berhasil dikonversi; selain itu, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metode




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metode




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) metode




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)